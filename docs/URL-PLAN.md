# 《黑蝠女王殿》獨立網址方案

## 第一階段：免費正式網址

獨立 GitHub repository：

`BJ-1996/black-bat-queen-shrine`

GitHub Pages 網址：

`https://bj-1996.github.io/black-bat-queen-shrine/`

《黑山觀人／七曜》留在原本主站，《黑蝠女王殿》完全獨立。

## 第二階段：獨立品牌網域

等產品穩定後，再購買自訂網域並綁到 GitHub Pages 或其他託管服務。

候選命名方向：

- `blackbatqueen.*`
- `batqueen.*`
- `queen-shrine.*`
- `blackbatshrine.*`

實際購買前需重新查詢網域是否可註冊。

## GitHub Pages 設定

1. 預設分支使用 `main`。
2. GitHub → Settings → Pages。
3. Build and deployment → Source 選擇 **GitHub Actions**。
4. Push 到 `main` 後，`.github/workflows/pages.yml` 會部署網站。

所有 PWA 路徑均使用相對路徑，因此能在 `/black-bat-queen-shrine/` 子路徑正常工作。
