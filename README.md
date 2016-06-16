# my-first-vue-project

## 安装步骤

1. Clone 至本地；
2. 检查本机是否已安装 Node.js 和 NPM, 如没有，请自行安装；
3. 安装 `vue-cli` package:
   
   ```bash
   sudo npm install -g vue-cli
   ```

4. 安装依赖：
   
   ```bash
   # swith to local project directory
   $ cd my-first-vue-project

   # install all dependencies listed in `package.json`
   $ npm install
   ```

4. 安装 `vux` NPM package：
   
   ```bash
   # in local project directory
   $ npm install vux
   ```

4. 运行：
   
   ```bash
   # in local project directory
   $ npm run dev
   ```

   此时，在浏览器中打开 `http://localhost:8088`, 就能看到项目主页。如果出现异常，请根据错误信息自行搜索解决；

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
