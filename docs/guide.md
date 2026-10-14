# 使用指南

## 本地预览

```bash
pip install -r requirements.txt
mkdocs serve
```

然后打开 <http://127.0.0.1:8000/> 即可预览。

## 本地构建

```bash
mkdocs build
```

构建产物会输出到 `site/` 目录（已被 `.gitignore` 忽略）。

## 自动化部署

推送到 `main` 分支后，`.github/workflows/deploy-pages.yml` 会：

1. 安装 MkDocs 及其主题依赖；
2. 执行 `mkdocs build`；
3. 把构建结果上传为 Pages 制品；
4. 发布到 GitHub Pages。
