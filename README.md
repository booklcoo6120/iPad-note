# 手寫筆記

iPad 與 Apple Pencil 用的手寫筆記網頁 App。

> **這是個人使用的倉庫。** 只為了自己的需求而做，不接受功能請求，也不提供使用支援。歡迎參考，但請自行承擔使用風險。

## 動機

原本使用的手寫筆記 App「Freenotes（自由ノート）」更新後改成付費才能使用。為了繼續免費、放心地在 iPad 上手寫筆記，就和 AI（Claude）一起做了這個功能相近的替代品。

## 使用方法

1. 用 iPad 的 Safari 打開：<https://booklcoo6120.github.io/iPad-note/>
2. 點「分享 → 加入主畫面」，之後從主畫面的圖示打開，就會以全螢幕 App 的方式執行。
3. 按「新筆記本」開始書寫，或用「匯入 PDF」直接在講義上寫。

**資料儲存**
- 筆記只存在你自己裝置的瀏覽器裡，**不會上傳到任何伺服器**，也不在這個倉庫裡。
- 換裝置或清除瀏覽器資料前，請先在首頁「⋯ → 備份全部筆記」匯出備份檔。

## 主要功能

- Apple Pencil 書寫（鋼筆有筆壓／原子筆粗細一致）、螢光筆、橡皮擦、套索
- 防手掌誤觸、手勢（雙指點一下＝復原，單指點一下＝快捷選單）
- 多本筆記本、橫線／方格／點陣紙張、左右翻頁或上下捲動
- 匯入 PDF 並直接書寫、插入圖片、截圖、拷貝／貼上
- 匯出 PNG／PDF、備份與還原
- 匯入 Freenotes（`.freenotes`）與 Saber（`.sba`、`.sbn2`）的筆記

## 聲明與授權

- 本專案與 Freenotes、Saber 及其開發者沒有任何關係。匯入功能是以自己的檔案分析而成，可能無法正確讀取所有檔案。
- 使用的第三方程式：
  - [PDF.js](https://github.com/mozilla/pdf.js)（Apache License 2.0）
  - [perfect-freehand](https://github.com/steveruizok/perfect-freehand)（MIT License）
