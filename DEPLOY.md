# 星流部署说明

这个目录是一个完整的静态网站，不需要 Node.js、数据库或后端接口。Three.js、MediaPipe、两套 WASM 和手部识别模型都已经包含在目录中。

## 部署要求

- 必须使用 HTTPS，手机和非本机电脑上的浏览器才会允许网页访问摄像头。
- 托管平台必须原样保留目录结构。
- `.wasm` 文件应以 `application/wasm` 返回。Netlify、Vercel、Cloudflare Pages 和 GitHub Pages 会自动正确处理。

## 最简单的发布方式

1. 解压 `starflow-web.zip`。
2. 将解压后的整个目录上传到 Netlify Drop、Cloudflare Pages、Vercel 或 GitHub Pages。
3. 打开平台生成的 HTTPS 地址。
4. 点击“开启摄像头”并允许摄像头权限。

## 浏览器范围

推荐使用当前版本的 Chrome、Edge、Safari 或 Firefox。页面会根据屏幕尺寸和可用内存自动调整粒子数量与渲染倍率。无法使用摄像头时，鼠标拖动或触屏按住拖动仍可体验完整粒子交互。

## 离线使用

第一次完整打开后，PWA 服务工作线程会缓存页面、识别模型和渲染资源。之后在相同浏览器中可以离线重新打开。摄像头权限仍由浏览器和操作系统控制。
