收藏掃描 — iPhone PWA 測試版

部署 GitHub Pages：
1. 建立新的 GitHub repository（例如 collection-scan）。
2. 上傳本 ZIP 解壓縮後的四個檔案至 repository 根目錄：index.html、manifest.webmanifest、sw.js、icon.svg。
3. 在 Settings > Pages，Source 選 Deploy from a branch，Branch 選 main、/(root)，儲存。
4. 等待部署完成，使用 GitHub Pages 提供的 https 網址，在 iPhone Safari 開啟。
5. Safari 分享 > 加入主畫面。

注意：
- 這是測試版，照片只存於此網站在此裝置的瀏覽器資料庫，並未上傳 GitHub。
- 清除網站資料或移除 App 可能造成照片遺失，請定期使用設定中的匯出備份。
- 首次開啟需網路，後續離線支援須實機測試。
- 相似搜尋是輕量特徵比對，可能漏判或誤判，請自行人工確認。
