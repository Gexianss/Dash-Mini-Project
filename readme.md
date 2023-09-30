1. 使用套件有Bootstrap、Font Awesome、Google Font、recaptcha
2. 主要以grid切出畫面，然後用flex做其他排版
3. 主畫面用position z-index做圖片重疊
4. Hover的樣式有的用css，有的用jQuery，只是為了表達我兩個方式都會
5. 輪播是用Bootstrap的Carousel，然後再寫jQuery讓他抓Bootstrap的slide.bs.carousel，去改變圓點的樣式
6. 全部的script都用jQuery寫
7. 表格全選是找input的checkbox，然後prop checked屬性
8. 表格的數字是用replace定義,的位置，然後用toLocaleString()回傳值
9. 表單的 <option> 是寫迴圈讓他跑30個
10. 機器人是找google的recaptcha api