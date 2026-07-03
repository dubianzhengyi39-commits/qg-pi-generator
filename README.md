# 报价 PI 生成工具

这是一个纯静态网页项目，可直接部署到 GitHub Pages。

## 发布后会得到什么

- 一个固定公网网址
- 手机、电脑、别人都可以直接打开
- 不依赖本地 `file://` 路径

## 项目文件

- `index.html`：主页面
- `xlsx.full.min.js`：SheetJS 本地依赖
- `.nojekyll`：让 GitHub Pages 不走 Jekyll
- `.github/workflows/pages.yml`：自动部署工作流

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库。
2. 把这个目录里的所有文件上传到仓库根目录。
3. 打开仓库的 `Settings`。
4. 进入 `Pages`。
5. 在 `Build and deployment` 里选择 `GitHub Actions`。
6. 等待 workflow 运行完成。
7. GitHub 会给你一个公网网址。

## 以后怎么更新

1. 直接修改本地文件。
2. 提交并推送到 GitHub 仓库。
3. GitHub Pages 会自动更新公网页面。

## 说明

- 这是纯前端静态站，所有数据都保存在浏览器本地。
- 历史版本、留痕记录保存在本机浏览器 `localStorage`，不会自动上传。
- 如果你想长期保留客户留痕，建议同时导出 JSON 备份。

