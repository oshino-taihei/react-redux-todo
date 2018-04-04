# react-redux-todo
React-Reduxで作ったToDoリストアプリケーション
react-reduxを使用。

# githubページ
https://oshino-taihei.github.io/react-redux-todo

# githubページ公開手順
## gh-pagesインストール
```
$ npm i --save-dev gh-pages
```
## deployコマンド追加
package.jsonのscripts設定にdeployコマンドとhomepageにURLを記載する。
```
"scripts": {
    "deploy": "gh-pages -d build",
},
"homepage": "https://oshino-taihei.github.io/react-redux-todo",
```
## ビルド
```
$ npm run build
```
## デプロイ
```
$ npm run deploy
```

