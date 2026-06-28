# NLP 培訓師冥想引導能力 21 天自我練習器

這是一個可上架 GitHub Pages 的互動式 PWA，協助 NLP 培訓師用 21 天自我訓練，練習帶領學員進入安全、放鬆、專注且可學習的冥想狀態。

## 功能

- 21 天每日訓練計畫
- COACH State、米爾頓模式、同步與引導、次感官調整、心錨、未來投影
- 每日聲音穩定度、語言流暢度、安全場域感自評
- 冥想引導詞生成器
- 訓練紀錄儲存與複製
- PWA manifest、service worker、icon 與離線快取

## 檔案結構

- `docs/index.html`：主 App
- `docs/manifest.webmanifest`：PWA 設定
- `docs/sw.js`：離線快取
- `docs/icons/meditation-icon.png`：App icon
- `docs/assets/brand-mark.png`：首頁左上角品牌小圖
- `docs/assets/sun-cloud-header.png`：首頁 Header 主視覺
- `local-server.mjs`：本機預覽伺服器

## 本機預覽

```powershell
node .\local-server.mjs
```

預設網址：

```text
http://localhost:4174/
```

## GitHub Pages 上架

1. 將此資料夾內容上傳到 GitHub repository。
2. 到 `Settings > Pages`。
3. Source 選 `Deploy from a branch`。
4. Branch 選 `main`，資料夾選 `/docs`。
5. 等待 GitHub Pages 發布完成。

PWA 安裝與 service worker 需要在 `localhost` 或 HTTPS 網址下才會啟用。
