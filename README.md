# Chronos — Standalone（單檔版）

歷史事件流程圖 App 的 **單一** `index.html`，可直接上傳 GitHub Pages。

## 用法

1. 把本資料夾的 `index.html` 丟到 GitHub repo 根目錄
2. Settings → Pages → Branch: `main` → `/ (root)` → Save
3. 開啟 `https://<你的帳號>.github.io/<repo名>/`

## 說明

- `styles.css`、`app.js`、`config.js`、logo 皆已內嵌
- 仍使用 CDN：Google Fonts、Supabase JS
- Supabase 請在 App 內設定，或搜尋 `CHRONOS_CONFIG` 改預設公開值（勿放 secret）
- AI API Key 在網頁設定中填寫，存在 localStorage

來源：多檔版 `Desktop/history-flow/` 打包產生。