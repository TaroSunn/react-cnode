# 项目初始化

`.gitignore`文件用于忽略不需要提交文件夹,比如`node_modules`文件夹

文件的内容就是要忽略文件夹或文件的名称

## 项目简介
使用`react`、`webpack`等技术,模仿cnode网站


`yarn add webpack webpack-cli -D`安装webpack

`yarn add react react-dom` 安装react、react-dom

`build`文件夹用于存放工程化配置文件
`webpack.config.js`用于配置webpack
`client`文件夹用于存放前端相关文件
`client`中的`app.js`是入口文件

webpack

`entry`入口文件配置

`output`打包后输出的文件配置

`output.filename`打包后输出文件的名称.
`output.path`打包后输出文件的地址

`package.json`定义build 命令 `"build": "webpack --config build/webpack.config.js"` `--config`指定配置文件的地址

webpack4.x版本需要通过`webpack-cli`才可以打包

想要webpack支持react需要安装loader,`babel-loader`、`babel-core`,以及配置`.babelrc`需要安装`babel-preset-es2015`、`babel-preset-es2015-loose`、`babel-preset-react`

`module`、`module.rules`



