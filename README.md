# threejs scaffold

## Description

This scaffold only has simplest function to use threejs which is the cube example for webpack

# Install

To install this, you can follow the codes.
'folderName' can be any folder name

You need install yarn before using

```bash
npm install yarn -g
```

and then

```bash
npx create-webpack-threejs [folderName]
cd [folderName]
yarn install
yarn start
```

## start example

```bash
yarn start
```

## Content

-   dev config `webpack.config.dev.js`
-   -   babel
-   -   css module
-   -   html template
-   -   devServer

-   prod config `webpack.config.prod.js`
-   -   css extract
-   -   hash8 filename
-   -   copy public
-   -   split chunks

> You can modify the `output.publicPath` configuration in `webpack.config.prod.js` to set the url prefix for static resources.

## THANKS

The npmjs manage for installing for npx almost from my senior [IanYet](https://github.com/IanYet/create-webpack-slim)

## 说明

-   本脚手架仅为最简单的 cube 样例，可供 webpack 使用

# 安装

必须已安装 [node.js](http://nodejs.org/)

并已安装 yarn

如未安装 yarn 可通过

```bash
npm install yarn -g
```

若已安装 yarn，可直接在根目录运行

```
npx create-webpack-threejs [folderName]
cd [folderName]
yarn install
```

## 启动样例

运行

```bash
yarn start
```

即可

## 感谢

上传至 npmjs 的方法是来源于偶的同事，感谢他([IanYet](https://github.com/IanYet/create-webpack-slim))
