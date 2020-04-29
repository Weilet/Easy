# Easy
An easy theme for Pelican

自用Pelican主题，改造自[此博客](https://xuanwo.io/)

### 更新：

#### 2020-02

---

- BackToTop组件
- 黑暗模式
- Gitalk评论系统
- Google Analytics
- 代码高亮
- 添加了TOC
- 添加了归档时间线

#### 2020-03

---

- SEO优化
- 黑暗模式优化
- 将Gitalk配置、Google analystic配置和主题解耦

#### 2020-04

---

- 移除Gitalk
- 移除BackToTop组件
- 移除归档时间线

### 安装：

1. 于博客目录克隆此仓库

   ```shell
   git clone https://github.com/Weilet/Easy.git
   ```

2. 于/content/pages/中编写 blogroll.md 和 about.md

   ```markdown
   ;blogroll.md
   # 友链
   
   ## 友人A
   [一句话](链接)
   
   ## 友人B
   [一句话](链接)
   ```

   ```markdown
   ;about.md
   
   # I am a cool guy.
   # that's all.
   ```

4. 于pelicanconf.py中配置Google Analytics

   ```python
   GITALK = {
       'clientID': '1234567890',
       'clientSecret': 'abcdefghijklmnopqrst',
       'repo': 'Mike.me',
       'owner': 'Mike',
       'admin': ['Mike']  
   }
   ```

4. 安装主题

   ```shell
   pelican-themes -i easy
   ```

### 实例
[我的博客](https://weilet.me)

