# 我的餐廳清單
餐廳清單匯集了使用者喜歡的餐廳，可以查看餐廳的簡易資訊，點擊可以查看各餐廳的詳細資料。使用者也可以透過搜尋餐廳名稱、餐廳類別找到清單中符合的餐廳。
## 功能列表
* 使用者可以在首頁看到所有餐廳與簡單資料：
  * 餐廳照片
  * 餐廳名稱
  * 餐廳分類
  * 餐廳評分
* 使用者可以再點進去看餐廳的詳細資訊：
  * 類別
  * 地址
  * 電話
  * 描述
  * 圖片
* 使用者可以透過搜尋餐廳名稱來找到特定的餐廳
* 使用者可以透過搜尋餐廳類別來找到特定的餐廳
## 環境建置
* Nvm 1.1.11
* Node.js 20.17.1
## 使用工具
* Express 4.19.2
* Express-handlebars 8.0.1
* Bootstrap
* Font Awesome
## 頁面樣式與資料
* [首頁樣式](https://codepen.io/alpha-camp/pen/yrLbrZ)：用於main.hbs, index.hbs, style.css
* [餐廳detail樣式](https://codepen.io/alpha-camp/pen/JVjNgG)：用於resturant.hbs, style.css
* [餐廳資料](https://drive.google.com/open?id=1W-BD9-c8zJRYCwAD8yhqQdLwcUdN8GZi)：restaurant.json
## 專案安裝流程
1. 開啟終端機到個人資料夾，將檔案複製下來
```
$ git clone https://github.com/shineni1031/restaurantList.git
```
2. 進入到此專案的資料夾
```
$ cd restaurantList
```
3. 安裝套件
    $ npm i express
    $ npm install -g nodemon
    $ npm install express-handlebars
4. 使用nodemon
```
$ nodemon app.js
```
5. 終端機顯示以下文字，即可打開瀏覽器輸入 http://localhost:3000 查看與使用網站
```
express server is running on http://localhost:3000
```
## 專案畫面
![首頁](https://i.imgur.com/Rq1ObFM.jpeg)
![餐廳detail](https://i.imgur.com/pp2NRku.jpeg)
