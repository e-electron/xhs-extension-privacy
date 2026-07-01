小红书chrome插件隐私政策页面，Chrome 商店提审要求扩展程序提供一个隐私政策页面 URL，该 URL 必须满足：
1. 公网可访问
2. 内容直接写在 HTML 中（爬虫可读，不依赖 JS 渲染）
3. 现有页面 https://agree.xiaohongshu.com/h5/terms/ZXXY20230227002/-1 是 SPA 动态渲染，爬虫无法读取内容，无法直接用于提审。

因此在 GitHub 上创建一个公开仓库，上传纯静态 HTML 文件，开启 GitHub Pages 功能，获得一个 github.io 的公网地址，直接填入 Chrome 商店后台。
