# vue-blockchain

> A Vue.js project with blockchain core

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
# run deploy vue app to github page
1. yarn add -D gh-pages
2. create vue.config.js and add following code
```javascript
module.exports = {
  publicPath: process.env.NODE_ENV === 'production'
    ? '/vue-blockchain/'
    : '/'
}
```
3. change homepage field in the package.json
4. add "deploy": "gh-pages -d dist" to the script
5. Enjoy!!!!

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
