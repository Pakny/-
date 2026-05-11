# 白羽连连看 PWA

这是已经整理好的 PWA 项目。

## 文件说明

- `index.html`：游戏主文件，已加入 PWA manifest 和 service worker 注册代码
- `manifest.json`：安装到桌面/主屏幕时使用的应用信息
- `sw.js`：离线缓存文件
- `icons/`：应用图标

## 使用方式

1. 将整个文件夹上传到 GitHub Pages、Netlify、Vercel、Cloudflare Pages 等 HTTPS 网站。
2. 用手机浏览器打开网址。
3. Android Chrome：右上角菜单 → 添加到主屏幕 / 安装应用。
4. iPhone Safari：分享按钮 → 添加到主屏幕。

注意：直接双击本地 `index.html` 用 `file://` 打开时，PWA 安装和离线缓存通常不会生效。需要 HTTPS 或本地服务器。
