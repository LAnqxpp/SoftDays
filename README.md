# SoftDays / 软日 — 无文件夹网页包

只有 4 个 HTML 文件（CSS、Logo 已内嵌）。每个文件含 **中文 / English / 日本語**。

| 文件 | App Store 用途 |
|------|----------------|
| `index.html` | 营销页（可选） |
| `support.html` | **支持网址** |
| `privacy.html` | **隐私政策网址** |
| `terms.html` | 用户协议（可选） |

邮箱：`azir_likes@126.com`

## 推到 Git（命令行，不必网页传文件夹）

在 GitHub 新建**空仓库**后：

```bash
cd AppStoreMaterials/publish
git init
git add index.html support.html privacy.html terms.html README.md
git commit -m "Add SoftDays App Store pages (zh/en/ja, standalone)"
git branch -M main
git remote add origin <你的仓库 HTTPS 或 SSH 地址>
git push -u origin main
```

开启 GitHub Pages：Settings → Pages → Branch `main` → `/ (root)`。
支持链接示例：`https://<用户名>.github.io/<仓库名>/support.html`
