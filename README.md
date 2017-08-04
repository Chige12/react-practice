Reactを勉強するぞ！
==================

Reactをちゃんと勉強しないとと思って開始。

## 参考にしたサイトメモ

* [BYOS](http://andrewhfarmer.com/build-your-own-starter/#1-git)

* [.gitignoreについて](http://qiita.com/y_minowa/items/e3d8513dc31c1b378e0d)
* [Setting up Babel 6](https://babeljs.io/blog/2015/10/31/setting-up-babel-6)
* [babel.preset-react](https://www.npmjs.com/package/babel-preset-react)
* [babel-preset-latest](https://babeljs.io/docs/plugins/preset-latest/)
* [npm installの–saveと–save-devの違い](http://the2g.com/2280)
* [webpack.config.jsの読み方、書き方](http://dackdive.hateblo.jp/entry/2016/04/13/123000)
* [Webpack はじめの一歩](http://qiita.com/kompiro/items/8337f28271b66957780e)
* [webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware)

### Usage
Start the development server with this command:
```
npm start
```

### Setup
```
npm install
```

### Compile
```
npm run compile
```


## 問題
### reactのinstallで権限エラー？
```
npm install --save react react-dom
npm ERR! path C:\Users\Chige\Desktop\project\react-practice\node_modules\fsevents\node_modules\rc\node_modules
npm ERR! code EPERM
npm ERR! errno -4048
npm ERR! syscall scandir
npm ERR! Error: EPERM: operation not permitted, scandir 'C:\Users\Chige\Desktop\project\react-practice\node_modules\fsevents\node_modules\rc\node_modules'
npm ERR!  { Error: EPERM: operation not permitted, scandir 'C:\Users\Chige\Desktop\project\react-practice\node_modules\fsevents\node_modules\rc\node_modules'
npm ERR!   stack: 'Error: EPERM: operation not permitted, scandir \'C:\\Users\\Chige\\Desktop\\project\\react-practice\\node_modules\\fsevents\\node_modules\\rc\\node_modules\'',
npm ERR!   errno: -4048,
npm ERR!   code: 'EPERM',
npm ERR!   syscall: 'scandir',
npm ERR!   path: 'C:\\Users\\Chige\\Desktop\\project\\react-practice\\node_modules\\fsevents\\node_modules\\rc\\node_modules' }
npm ERR!
npm ERR! Please try running this command again as root/Administrator.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Chige\AppData\Roaming\npm-cache\_logs\2017-08-03T12_06_02_083Z-debug.log
```
