# TOGETHER · 那些日子

朋友照片纪念网站。三个完整视口，支持滚轮、键盘及触控翻页，照片大图查看，文字与按钮牵引反馈，ClickSpark 点击火花，以及可拖动收起的首屏标题。

纯 HTML、CSS、JavaScript，无需安装依赖或构建。入口是根目录 `index.html`，照片与字体位于 `assets/`，请保持目录结构。

GitHub Pages 使用 `main` 分支的根目录发布；`.nojekyll` 关闭 Jekyll 处理。所有素材均随仓库提供，页面不依赖电脑磁盘绝对路径。

尊重 `prefers-reduced-motion` 设置。文字为可访问的 DOM 内容，照片支持键盘查看与关闭。

点击火花算法根据用户提供的 React Bits ClickSpark 源码移植；第三屏照片簇布局参考 Stridr，并使用个人照片、纪念文案与独立宿主交互。
