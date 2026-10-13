商品成本計算器 PWA｜GitHub Pages 部署指南

網址：https://rt516817.github.io/buycount/

1. 進入 GitHub 的 buycount 儲存庫。
2. 將 ZIP 解壓縮後的 index.html、manifest.webmanifest、sw.js 與 icons 資料夾，上傳到 GitHub Pages 發布目錄（通常為儲存庫根目錄）。
3. 保持檔案相對位置不變；等待 GitHub Pages 部署完成。
4. 在手機 Chrome / Safari 開啟 https://rt516817.github.io/buycount/。
5. Android：瀏覽器選單 → 安裝應用程式 / 加入主畫面。
   iPhone：Safari → 分享 → 加入主畫面。
6. 第一次需連網開啟一次，之後可離線使用。

若更新後仍看到舊版，請重新整理頁面，必要時關閉並重開已安裝的 App。
注意：使用 file:// 直接打開 index.html 可計算，但無法註冊 Service Worker；PWA 安裝與離線快取須在 HTTPS 網址下使用。
