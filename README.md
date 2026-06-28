# kkSaMa-123 的博客

这是一个纯静态个人博客，适合部署到 GitHub Pages。

## 本地预览

直接打开 `index.html`，或运行：

```bash
python3 -m http.server 8080
```

然后访问 `http://localhost:8080`。

## 新增文章

1. 复制 `posts/start.html`，改成新的文章文件名。
2. 修改新文件里的标题、日期、分类和正文。
3. 在 `posts.js` 顶部新增一条文章记录。

## 发布到 GitHub Pages

仓库推送到 GitHub 后，在仓库设置中打开 Pages，选择 `GitHub Actions` 作为来源。
本仓库已包含自动发布配置：`.github/workflows/pages.yml`。
