# Simple Twitter

![page_1](./loginv1.png)

![page_2](./indexv1.png)

![page_3](./userv1.png)


## 功能
* 使用者在首頁看到所有人的 tweet
* 使用者可以點擊側邊的按鈕或直接在首頁上方的空白區輸入內容發佈屬於自己的推文
* 點擊任何一個 tweet 上的頭貼，可以查看該 tweet 詳情及回覆串
* 點擊任何一個 tweet 方塊中的 reply 圖示，可以對該 tweet 進行回覆
* 可在首頁看到每一則 tweet 被喜歡的數量，以及被回覆的數量
* 使用者可以編輯自己的：帳號/名稱/email/密碼/大頭像/封面/自我介紹

## 設定安裝

Clone repository to your local computer

```bash
git clone https://github.com/LettuceLu751103/twitter-fullstack-2020.git
```

Into the project folder

```bash
cd twitter-fullstack-2020
```

Install by npm

```bash
npm install
npm i nodemon
```

建立 MySQL 連線 (帳號: root / 密碼: password)

在 MySQL Workbench 建立 database

```
create database ac_twitter_workspace;
```

執行 migration

```bash
npx sequelize db:migrate
```

執行 seeder

```bash
npx sequelize db:seed:all
```

參考 .env.example 建立屬於自己的 .env 檔

```bash
npm run dev
```

展示網址: https://boiling-bastion-43629.herokuapp.com/signin

admin:登入帳號 root@example.com，密碼 12345678
一般使用者:登入帳號 user1@example.com，密碼 12345678


## Built with
* "bcrypt-nodejs": "0.0.3",
* "bcryptjs": "^2.4.3",
* "body-parser": "^1.19.0",
* "chai": "^4.2.0",
* "connect-flash": "^0.1.1",
* "express": "^4.16.4",
* "express-handlebars": "^5.2.0",
* "express-session": "^1.17.2",
* "faker": "^4.1.0",
* "imgur-node-api": "^0.1.0",
* "method-override": "^3.0.0",
* "mocha": "^6.0.2",
* "moment": "^2.29.1",
* "multer": "^1.4.4",
* "mysql2": "^1.6.4",
* "passport": "^0.4.0",
* "passport-local": "^1.0.0",
* "pg": "^8.7.1",
* "sequelize": "^4.42.0",
* "sequelize-cli": "^5.5.0",
* "sinon": "^7.2.3",
* "sinon-chai": "^3.3.0"


## Author
Lettuce Lu, 翁 國翔
