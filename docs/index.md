# 欢迎来到我的文档站点

这是一个使用 **MkDocs** 搭建、并通过 **GitHub Actions** 自动部署到 **GitHub Pages** 的静态文档站点。

## 它是怎么工作的

1. 把 `docs/` 目录下的 Markdown 文件推送到 `main` 分支；
2. GitHub Actions 自动触发，用 MkDocs 把 Markdown 构建成静态网站；
3. 构建产物自动发布到 GitHub Pages，几秒后即可访问。

!!! note "关于本页"
    你看到的这个页面就是自动部署的结果——本地没有手动执行过任何构建命令。
