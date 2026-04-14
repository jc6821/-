手機直接拿 APK 的做法：

1. 到 GitHub 建一個新的空白 repository。
2. 把這個壓縮檔全部解壓後上傳到 repository 根目錄。
3. 上傳完成後，進入 GitHub 的 Actions 分頁。
4. 點「Build APK」。
5. 點「Run workflow」。
6. 等幾分鐘，進入那次執行結果。
7. 在 Artifacts 區下載 english-learning-debug-apk。
8. 解壓後得到 app-debug.apk，直接安裝。

這個 App 會直接讀取 app/src/main/assets/index.html。
我已經把完整單字資料放在裡面了，不是空殼。
