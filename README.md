[@rokuzeudon](https://github.com/rokuzeudon)のはてなブログ開発用テーマです。
株式会社はてな様のデザインテーマ[Hatena-Blog-Theme-Boilerplate](https://github.com/hatena/Hatena-Blog-Theme-Boilerplate)をベースにしています。

# 条件

- [Node.js](https://nodejs.org/)

# インストール

```
$ git clone git@github.com:rokuzeudon/6q-hatenablog_theme-square_plates.git
$ cd 6q-hatenablog_theme-square_plates
$ npm install
```

# 始め方

SCSSファイルのコンパイルと監視
`$ npx parcel scss/style.scss -d build`

minyfy
`$ npx parcel build scss/style.scss`

# 構造

```
6q-hatenablog_theme-square_plates/
┣┳ scss/
┃┗┳ lib/
┃ ┗ style.scss
┗┳ build/
 ┗ style.css
```
