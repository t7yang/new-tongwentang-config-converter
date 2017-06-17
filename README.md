# 新同文堂舊版設定檔轉新版設定檔

網址：https://rawgit.com/t7yang/new-tongwentang-config-converter/master/index.html

#### 使用步驟
- 從舊版套件匯出設定檔檔案
  - tongwen_filter.txt
  - tongwen.xml
- 取得現有新版本的設定檔
  - Firefox: 目前只能自己去找`profiles/browser-extension-data/tongwen@softcup/storage.js`
  - chrome: `套件直接匯出設定檔`
- 把上述的設定檔貼到對應的欄位中
- 根據你的瀏覽器選擇產生新的設定檔
- 寫入新的設定檔
  - Firefox：覆寫 `storage.js`
  - 透過套件匯入新的設定檔
