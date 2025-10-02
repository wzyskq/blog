# Welcome to my blog ~

**部署方案：Quarto + Github Page**

- 首次部署时使用 `quarto publish gh-pages` 命令创建并自动推送 `gh-pages` 分支
- 后续只需推送 `main` 分支，Github Actions 会自动将 `main` 分支的内容渲染并部署到 `gh-pages` 分支
