# dojo-webpack-plugin-sample

[Sample application](https://openntf.github.io/dojo-webpack-plugin-sample/test.html) demonstrating the use of [dojo-webpack-plugin](https://github.com/OpenNTF/dojo-webpack-plugin) with [webpack](https://webpack.github.io/).  The sample can be run as a webpack application (the default) or as an [unpacked application](https://openntf.github.io/dojo-webpack-plugin-sample/test.html?nopack=1) that uses the Dojo loader by specifying the ?nopack=1 query arg in the URL.  It demonstrates how to construct a [Dojo loader config](https://github.com/OpenNTF/dojo-webpack-plugin-sample/blob/master/js/loaderConfig.js) that can be used in both weback and non-webpack versions of a Dojo application.  You may want to support non-webpack versions during the development phase of your application in order to avoid build overhead during development.

```
npm install
```
Production
```
npm run build
```
Development server
```
npm run start
```
