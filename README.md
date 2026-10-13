# TOGETHER · 那些日子

朋友照片纪念网站。三个完整视口，支持滚轮、键盘及触控翻页，照片大图查看，文字与按钮牵引反馈，ClickSpark 点击火花，以及可拖动收起的首屏标题。

在线网址：https://m19712267929.github.io/my-friend/

纯 HTML、CSS、JavaScript，无需 npm 安装。入口是根目录 `index.html`。字体位于 `assets/fonts/`；照片和画作分别保存在 `assets/photos.zip`、`assets/artwork.zip`。本地使用时，将两个 ZIP 解压到 `assets/` 目录，保留包内目录结构，然后打开 `index.html`。

GitHub Pages 由 `.github/workflows/pages.yml` 自动发布：读取 `main` 分支，解压素材并复制静态文件到 `_site/`，再部署到 Pages。所有素材随仓库提供，页面不依赖电脑磁盘绝对路径。

尊重 `prefers-reduced-motion` 设置。文字为可访问的 DOM 内容，照片支持键盘查看与关闭。

点击火花算法根据用户提供的 React Bits ClickSpark 源码移植；第三屏照片簇布局参考 Stridr，并使用个人照片、纪念文案与独立宿主交互。
