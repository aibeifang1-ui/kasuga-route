春日站往返・GitHub Pages 拆分版

这版专门为 GitHub 网页上传做了拆分：
- index.html：约几十 KB，不再内嵌大底图
- map.png：底图单独保存
- sw.js：离线缓存
- manifest.webmanifest：主屏幕/PWA
- apple-touch-icon.png：iPhone 主屏幕图标
- .nojekyll：GitHub Pages 静态发布辅助文件

上传方法：
1. 解压本 ZIP。
2. 把里面全部文件上传到仓库根目录。
3. Commit changes。
4. Settings → Pages → Deploy from a branch。
5. Branch 选 main，目录选 /(root)，Save。
6. 发布后用 Safari 打开网址。
7. 首次联网完整打开一次后，再“添加到主屏幕”。

重要：
index.html 与 map.png 必须放在同一层目录。
