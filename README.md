# To Do List ft.Sequelize
本專案是使用 SQL 資料庫製作的待辦清單，提供使用者登入、新增、修改、刪除、確認完成事項等功能。

## 專案首頁
<img src="https://github.com/pchu128/todo-sequelize/blob/master/index.png" width="600px" height="450px">

## 功能導覽
- 首頁
  - 瀏覽代辦清單
  - 新增代辦事項
  - 刪除代辦事項
  - 按鍵進入修改頁面
  - 按鍵進入修改頁面
  
- 詳細資訊頁面
  - 觀看代辦清單詳細資訊
  - 按鍵進入修改頁面
  - 刪除代辦事項
  
- 新增、修改頁面
  - 可自行新增或修改代辦事項所有資訊
  - 可將代辦事項狀態修改為已完成

## 系統需求
- 終端機
- Node.js
- Visual Studio Code
- SQL
- Sequelize

## 如何安裝？
首先開啟終端機，遵循以下步驟。
```
//將專案複製到電腦中
git clone https://github.com/pchu128/todo-sequelize.git

//進入專案資料夾
cd todo-sequelize

//安裝npm套件
npm install

//安裝種子資料
npm run seed

//執行專案
npm run dev
```
終端機顯示 "Express is running on http://localhost:3000" 後，即可開啟瀏覽器進入 http://localhost:3000 測試功能。

## Built With
- express
- express-handlebars
- method-override
- bcryptjs
- express-session
- passport
- passport-local