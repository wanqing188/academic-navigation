# Academic Navigation

一个无需构建步骤的静态网址导航页面。网页文件和 `logos/` 目录会直接发布到 GitHub Pages。

## 部署到 GitHub Pages

1. 将仓库推送到 `main` 分支。
2. 在 GitHub 仓库打开 **Settings → Pages**，将 **Build and deployment → Source** 设置为 **GitHub Actions**。
3. 打开 **Actions**，查看 **Deploy GitHub Pages** 工作流。之后每次推送到 `main` 都会自动发布；也可以在 Actions 页面手动运行工作流。
4. 工作流完成后，在其运行摘要的 `github-pages` 环境中打开已发布的网址。此仓库的默认地址为 `https://wanqing188.github.io/academic-navigation/`。

该网站为纯静态页面，不需要安装依赖或执行构建命令。`.nojekyll` 文件用于让 Pages 原样提供仓库文件。

## 数据保存

收藏、最近访问、分类调整和自定义网址保存在当前浏览器的本地存储中，不会自动同步到其他设备。需要迁移时，可在页面中导出配置，再在另一台设备导入。
