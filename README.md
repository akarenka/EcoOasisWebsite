# 末日重構：綠洲避難所

開啟 `index.html` 即可遊玩。包含地圖、農田、畜牧、採集小遊戲、交易所、環境升級、露營車、音效及本機自動存檔。

## 部署到 GitHub Pages

1. 建立公開 GitHub repository，將 `index.html` 上傳至 repository 根目錄。
2. 開啟 Settings → Pages，在 Build and deployment 選擇 Deploy from a branch。
3. Branch 選 `main`、資料夾選 `/ (root)`，儲存設定。
4. 等待 Pages 完成部署後，開啟頁面顯示的網址。

## 存檔與帳號

進度儲存在瀏覽器的 localStorage。玩家信箱及名稱只是本機檔案標籤，不執行 Google 登入，也不會跨裝置同步。清除網站資料會刪除存檔。外部字型、圖示、Tailwind、Tone.js 和頭像佔位圖需要網路連線。
