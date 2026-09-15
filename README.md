# 黑蝠女王殿 V2｜獨立網站版

> 在黑暗裡，妳從不孤單。

這是《黑蝠女王殿》的獨立網站／PWA 母版，不依賴黑山觀人主站。

## 現有功能

- 手機優先、可安裝 PWA
- 女王主殿與每日參拜
- 黑蝠女王百籤，目前 36 支正式籤
- 六類籤：財運、感情、事業、人心、平安、破局
- 每日正式籤、收藏與籤簿
- 祈願簿與願望狀態
- 每日覆命與連續紀錄
- 財路五層：見財、擇財、聚財、守財、化財
- 女王抱抱互動
- 女王信件
- localStorage 本機保存
- GitHub Pages 自動部署工作流

## 本機預覽

不要直接雙擊 `index.html` 測試 Service Worker。請在這個資料夾啟動任一靜態 HTTP Server，例如：

```bash
python -m http.server 8080
```

然後開啟：

`http://localhost:8080/`

## 正式部署

建議 repo：

`BJ-1996/black-bat-queen-shrine`

詳細步驟見：`docs/URL-PLAN.md`

## 後續 V3

- 正式沈觀棋／黑蝠女王五套原創立繪
- 36 籤擴充成 100 籤
- Supabase 登入與跨裝置同步
- AI 女王陪伴
- AI 深度解籤
- Web Push
- 音樂與儀式音效
