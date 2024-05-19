# 概要

# 環境構築
- `npx create-react-app react_app_1_pokemon`
- `npm start`

# Vscodeプラグイン
- ES7+ React/Redux/React-Native snippets
    - rafce: 雛形が作られる
- Auto Rename Tag
    - 閉じタグも変わる
- Auto Close Tag
    - 閉じタグをつける
- HTML CSS Support
- HTML Snippets
    - 最近メンテされなくなって非推奨になっている
- Material Icon Theme
- Prettier - Code formatter
    - Format ON Save

# Chrome
- JSONVue

# ショトカット
- command + b
- command + Shift + e
- command + shift + x
- command + j
- command + a
- command + x
- option + ⇩

# 要件
- 下記APIを使用してください
```
「https://pokeapi.co/api/v2/pokemon」
「https://pokeapi.co/api/v2/pokemon/${id}」
```

- フォルダ構成は下記の形にしてください
```
- src
    - components/
        - Card/
            - Card.js
            - Card.css
        - Navbar/
            - Navbar.js
            - Navbar.css
    - utils
        - pokemon.js
    - app.css
    - app.js
```
- `Promise`、`Promise.all`を使用してください
- `then`を使用してください
- ボタンは`transition`と`transform`を使用使用してhoverしたら沈み込む形にしてください
- `display: grid;`と`grid-template-columns`と`gap`と`place-items`を使用するようにしてください
- `useState`と`useEffect`を使用してください
- データを読み込んでいる際は`ロード中`と表示してください