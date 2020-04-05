# nuxtcore

> nuxt core for nuxt project

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

***

## 專案目的

此為 NUXT SSR 的核心專案，方便未來開發 NUXT 專案時直接 fork 此專案，避免重新設定。

## 基礎設定
這邊將介紹一下此專案目前的設定。
* 這是一個 SSR 的專案，並非 SPA，若需要轉換為 SPA，可到 `nuxt.config.js` 裡將 mode 改為 `mode: 'spa'`，再用 `npm run dev --spa` 即可，剩下 build 與 deploy 方法可參考此篇[文章](https://www.hellosanta.com.tw/blog/web-page-is-built-by-using-nuxt-single-page-application-is-easy)。
* 開發的主要套件目前是尚未安裝的，例如：Bootstrap、vuetify。可根據個人開發習慣安裝，這邊介紹 Bootstrap 與 vuetify 的安裝方法(當然不一定只有此兩種套件，你也可以安裝自己喜歡的，或是不安裝。)