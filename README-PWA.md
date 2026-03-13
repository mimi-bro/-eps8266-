# ESP-01S 继电器 PWA 部署说明

## 文件
- `index.html`：主页面
- `manifest.webmanifest`：PWA 清单
- `sw.js`：离线缓存脚本
- `assets/`：图标资源

## 部署到 GitHub Pages
1. 新建一个 GitHub 仓库。
2. 把当前目录下这些文件上传到仓库根目录。
3. 仓库里进入 `Settings -> Pages`。
4. `Source` 选择 `Deploy from a branch`。
5. 选择 `main` 分支和 `/root` 目录。
6. 等待 GitHub Pages 生成访问链接。

## 手机安装
1. 用安卓 Chrome 打开 GitHub Pages 链接。
2. 页面若出现“安装控制页”按钮，直接点击。
3. 如果没出现，点浏览器右上角菜单，选“添加到主屏幕”或“安装应用”。

## 提醒
- 当前页面内含巴法云 UID，只建议你自己使用。
- 如果以后要公开给别人用，建议把 UID 移到后端接口。
