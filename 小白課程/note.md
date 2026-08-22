
# 基本框架
## 主區塊
- DOCTYPE 告知瀏覽器檔案類型
- html 整張網頁
- head 設定編碼、要載入的檔案等
- body 網頁內容

## 其他標籤
- title 網頁標題
- meta 設定編碼、後設資料


# 註解、基本標籤
https://youtu.be/LD1PhxcYKRI?si=PIWSc2I4laW9K5t-
- 註解
- h 標題
  - 範圍 h1~h6
  - h1 最大，通常只有一個
  - h6 最小
- b 粗體字
- i 斜體字
- br/ 換行
- hr/ 水平線
- 省略結尾標籤 </>，如：br/ hr/。meta 標籤也能改寫為 meta/


# 連結、圖片
https://youtu.be/14Zc6hA5OP8?si=M837AzyVP--9fKPH
- 縮排
- a 連結
  - herf="{url}"
  - herf="{path}"
    - path 當前頁面為出發點，結合資料夾 + 檔案名稱，來指向目標路徑
    - ../ 返回上層
- img /
  - src 資源路徑，可以是本地、也能來自其他 url
  - width 寬度
  - height 高度
  - 若只給 width or height 則會自動等比例縮放


  # 影片
  - video
    - src 來源
    - controls 啟用基本控制
    - width 寬度
    - height 高度
  - 嵌入網路影片
    - 以 Youtube 為例，分享 button 會產出 iframe 的代碼，直接使用即可