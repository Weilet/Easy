# Easy
An easy theme for Pelican

自用Pelican主题，改造自[此博客](https://xuanwo.io/)

### 更新：

- Back to Top，移动端一般自带，只给桌面添加了。
- 黑暗模式，原css上有黑暗模式的样式，却没有使用。于是简单地加了一个黑暗模式（判断时间后决定是否修改样式）
- Gitalk评论系统
- Google Analytics
- 重新编写了代码高亮
- 添加了TOC
- SEO优化
- 黑暗模式更换了实现，切换更加顺滑
- 将Gitalk配置、Google analystic配置和主题解耦

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

3. 于pelicanconf.py配置Gitalk

   ```python
   ANALYSTIC_ID = "1234567890"
   ```

4. 于pelicanconf.py配置Google Analytics

   ```python
   GITALK = {
       'clientID': '1234567890',
       'clientSecret': 'abcdefghijklmnopqrst',
       'repo': 'Mike.me',
       'owner': 'Mike',
       'admin': ['Mike']  
   }
   ```

5. 安装主题

  ```shell
  pelican-themes -i easy
  ```

### 实例
[我的博客](https://weilet.me)

