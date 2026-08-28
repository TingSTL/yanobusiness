店舖收支 PWA — GitHub Pages 上線 SOP
===================================

這個資料夾可以直接上傳 GitHub Pages。

檔案內容
--------
index.html
manifest.webmanifest
sw.js
.nojekyll
icons/icon-192.png
icons/icon-512.png

你的帳務資料不在這些檔案裡。
日常帳目仍存在手機 / 電腦瀏覽器的 IndexedDB。
JSON 備份請放 Google Drive，不要上傳 GitHub。

GitHub Pages SOP
----------------

1. 到 GitHub 建立帳號
2. New repository
3. Repository name：shop-ledger
4. 選 Public
5. 建立 repository
6. Add file → Upload files
7. 把這個資料夾內的所有檔案上傳
8. Commit changes
9. Settings → Pages
10. Source：Deploy from a branch
11. Branch：main
12. Folder：/(root)
13. Save

網址通常會是：
https://你的GitHub帳號.github.io/shop-ledger/

iPhone 安裝
-----------
1. Safari 打開上面的網址
2. 分享
3. 加入主畫面
4. 開啟「作為網頁 App 打開」（若系統顯示）
5. 加入

Android 安裝
------------
1. Chrome 打開網址
2. 選單
3. 加入主畫面 / 安裝應用程式

換設備
------
舊設備：
備份與搬家 → 下載完整備份 → 把 JSON 放 Google Drive

新設備：
打開同一個 PWA 網址 → 備份與搬家 → 從備份恢復 → 選 JSON

更新程式
--------
日後若有新版：
只需要用新版 index.html / manifest / sw.js 覆蓋 GitHub repository。
網址不需要改。

重要：
GitHub 只放「程式」。
Google Drive 放「帳務備份 JSON」。
不要把帳務 JSON 上傳 GitHub。
