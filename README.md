# Juejin 个人简历网站

纯 HTML、CSS 和 JavaScript，可直接部署到 GitHub Pages，也可双击 index.html 在本地查看。

## 发布
1. 登录 GitHub，创建名为「你的用户名.github.io」的公开仓库。例如用户名为 juejin-demo，仓库名就是 juejin-demo.github.io。请使用你的真实 GitHub 用户名。
2. 解压本压缩包，将 index.html、style.css、script.js、favicon.svg 和 README.md 上传到仓库根目录。不要上传 ZIP 本身，也不要把 index.html 放在多余的一层文件夹内。
3. 在仓库 Settings → Pages 中选择 Deploy from a branch，分支 main，目录 /(root)，点击 Save。
4. 等待发布完成；在 Settings → Pages 查看 GitHub 提供的网站链接。如失败，在 Actions 查看运行记录。

## 修改
- index.html：个人介绍、教育经历、研究方向、成果及联系方式。
- style.css：颜色、字体、布局、手机适配及打印样式。
- script.js：打印按钮与页脚年份。
- favicon.svg：浏览器标签页图标。

你可以直接在 GitHub 网页打开文件，点击编辑按钮修改，再 Commit changes 保存；推送到发布分支后，GitHub Pages 会更新网站。

当前包含 Juejin、河海大学、博士生和水文水资源信息。其他个人信息明确标为待补充，请在发布前核对。默认 GitHub Pages 网站公开访问，请只上传希望公开的简历内容。

## 添加 PDF 简历下载
上传你的 resume.pdf 到根目录，并在 index.html 中合适位置加入：

<a href="./resume.pdf" download>下载简历 PDF</a>

现有「打印 / 保存 PDF」按钮调用浏览器打印功能，与下载预先上传的 PDF 是两种不同功能。

## 官方文档
- https://docs.github.com/en/pages/quickstart
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
