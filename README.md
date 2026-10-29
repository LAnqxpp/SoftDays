# 软日 SoftDays — App Store 网页资料

中文名：**软日** · 英文名：SoftDays  
语言：**中文（默认）** + **English**（`en/`）

本目录可直接托管到 GitHub Pages、Cloudflare Pages 或任意静态空间。

| 用途 | 中文 | English | Connect 字段 |
|------|------|---------|--------------|
| 产品页 | `index.html` | `en/index.html` | 营销网址（可选） |
| 支持 | `support.html` | `en/support.html` | **支持网址** |
| 隐私政策 | `privacy.html` | `en/privacy.html` | **隐私政策网址** |
| 用户协议 | `terms.html` | `en/terms.html` | 可选补充链接 |

每页右上角有 **中文 / EN** 切换；页面含 `hreflang` 互链。

## 建议填 Connect 的链接

- 支持网址：`…/support.html`（英文用户可点页内 EN）
- 隐私政策：`…/privacy.html`

若希望英文区直达英文页，也可把营销网址设为 `…/en/`。

## 本地预览

```bash
cd AppStoreMaterials
python3 -m http.server 8080
# http://localhost:8080
# http://localhost:8080/en/
```

## 上架前请替换

各页中的邮箱 `azir_likes@126.com`

## 结构

```
AppStoreMaterials/
  index.html          # 中文首页
  support.html
  privacy.html
  terms.html          # 用户协议
  en/
    index.html
    support.html
    privacy.html
    terms.html
  assets/
    styles.css
    logo.png
    logo-256.png
```
