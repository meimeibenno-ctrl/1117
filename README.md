# 暖日衣櫥｜小熊穿搭日記

純 HTML、CSS、JavaScript 的響應式穿搭小遊戲，無需建置或安裝套件。

## 本機預覽

直接以瀏覽器開啟 `index.html`，或在此資料夾啟動任意靜態檔案伺服器。

## 部署至 Vercel

1. 將此資料夾推送到 GitHub repository。
2. 在 Vercel 匯入該 repository。
3. Framework Preset 選擇 **Other**，Build Command 與 Output Directory 留空，部署即可。

## 功能

- 桌機拖放、手機點選穿搭；支援分類、脫下與隨機搭配。
- 正面、側面、背面切換，以及打招呼、跳舞、慵懶動作。
- 每件服飾有穿搭故事，收藏與會員示範資料使用瀏覽器 `localStorage`。

會員目前是前端展示流程，尚未連接安全的身分驗證、跨裝置同步或資料庫。正式開放會員前，需串接 Supabase、Firebase 等後端服務。
