# html-practice
HTML／Javascript／css等々の練習用リポジトリ

#browser-sync
### npmの準備とbrowser-syncのインストール
```
npm init -y
npm i -D browser-sync
```
### package.jsonの編集
```
"scripts": {
  "start": "browser-sync start --server --files '**/*'"
},
```
### HTMLサーバ起動
```
npm start
```
