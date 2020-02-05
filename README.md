# Easy
An easy theme for Pelican

自用Pelican主题，从[漩涡大佬](https://xuanwo.io/)这里copy过来的（曾经telegram过大佬，无果）。

### 按时间顺序，俺往原有的样式上添加了：

- Back to Top，移动端一般自带，只给桌面添加了。
- 黑暗模式，原css上有黑暗模式的样式，却没有使用。于是简单地加了一个黑暗模式（判断时间后决定是否修改样式）
- Gitalk评论系统

### 使用本主题，也相对方便：

- 在你的博客根目录克隆此项目 `git clone https://github.com/Weilet/Easy.git`。

- 按照Gitalk文档注册Github application，将ClientID等填写至/template/includes/_gitalk.html相应位置。
- 注册Google analytics，将跟踪代码填写到/template/includes/_head.html相应位置。
- 在your_blog/content/pages中创建blogroll.md以及about.md，它们分别对应友链页面和关于页面。
- 运行 `pelican-themes -i easy ` ，主题安装完成。

### 对于本主题，俺有以下期待：

- 重新编写代码高亮，现在的太丑了。
- 侧栏TOC，写过几次都太丑了。

### 实例
[我的博客](https://weilet.me)



