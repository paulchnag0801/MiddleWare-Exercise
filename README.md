# MiddleWare 實作練習

在 Node.js/Express 開發中，加入一支 middleware，將所有需求回應紀錄在 sever log 中。

## 功能

- 在伺服器接收請求時紀錄時間、URL、HTTP 請求方法
- 在伺服器回應請求時紀錄時間，並計算出從請求到回應的伺服器處理時間

### 安裝

1. 開啟終端機(Terminal)將此專案 Clone 至本機電腦

```
git clone https://github.com/paulchnag0801/MiddleWare-Exercise
```

2. 進入存放此專案的資料夾

```
cd middleware
```

3. 安裝 npm 套件

```
npm install
```

4. 啟動網頁伺服器

```
npm run dev
```

當 Terminal 出現以下文字表示成功連結本地伺服器

```
App running on port 3000
```

5. 在任一瀏覽器中輸入 http://localhost:3000 開始使用本專案

## 環境

- Node.js v14.17.1
- express v4.17.1
