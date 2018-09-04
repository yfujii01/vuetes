# vuetes

# 作成から公開まで

$ vue create webpack vuetes

全てENTER

$ cd vuetes

config/index.js修正

build内を修正する
---
assetsPublicPath: '/',
↓
assetsPublicPath: '',
---

$ npm install gh-pages --save-dev

package.jsonを修正
---
"scripts": {
    "deploy": "gh-pages -d dist"
  }
---

$ git add -A

$ git commit -m "commit"

$ git remote add origin ◯◯◯◯◯◯◯◯◯◯

$ git push master head

$ npm run deploy


> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
