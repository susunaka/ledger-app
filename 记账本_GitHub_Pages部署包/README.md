# 记账本 · GitHub Pages 版

这是一个纯静态、离线可用的个人记账 PWA。账目通过浏览器 `localStorage` 保存在当前设备，不会提交到 GitHub。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个 **Public** 仓库，建议命名为 `ledger-app`。
2. 解压本压缩包，将本目录内的所有文件上传到仓库根目录。必须让 `index.html` 直接位于仓库根目录，而不是再套一层文件夹。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中，将 **Source** 选择为 **Deploy from a branch**。
5. Branch 选择 `main`，Folder 选择 `/(root)`，点击 **Save**。
6. 发布地址通常为：`https://你的GitHub用户名.github.io/ledger-app/`。

## 添加到 iPhone 主屏幕

1. 用 iPhone 的 Safari 打开发布地址。
2. 点击“分享”。
3. 选择“添加到主屏幕”。
4. 保持“作为 Web App 打开”开启，然后点击“添加”。

## 重要说明

- GitHub 仓库中只有应用代码和图标，不包含你的账目。
- 账目保存在当前 iPhone 的浏览器本地存储中。
- 清除 Safari 网站数据、删除主屏幕 Web App 或更换网址前，先在应用设置中导出 JSON 备份。
- 修改应用文件后提交到 `main`，GitHub Pages 会重新发布。
