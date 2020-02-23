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

### 安装：

- 在博客根目录克隆此项目 `git clone https://github.com/Weilet/Easy.git`
- 按照[Gitalk文档](https://github.com/gitalk/gitalk)配置_gitalk.html
- 注册Google analytics，将跟踪代码填写至_head.html相应位置。
- 在/content/pages中创建blogroll.md以及about.md，它们分别对应友链页面和关于页面。
- 在终端中输入 `pelican-themes -i easy ` 安装主题。

### 实例
[我的博客](https://weilet.me)



