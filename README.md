# react-demo

----
## package.json -> dependencies

### react
React框架核心

### react-dom
React视图渲染的核心，基于React构建WebApp(==!react-native for app==)

### react-scripts
脚手架中对webpack打包命令的封装

### web-vitals
性能检测工具

----

## package.json -> scripts

### start
开发环境；在本地启动web server，预览打包内容

### build
生产环境；打包部署，打包的内容输出到dist目录

### test
unit test

### eject
暴露webpack配置规则（修改默认的打包规则）

----

## package.json -> eslintConfig
对webpack中eslint词法检测的相关配置

----

## packgae.json -> browserslistt
基于browsweslist规范，配置浏览器兼容情况
- postcss-loader + autoprefixer会给CSS3设置相关的前缀
- babel-loader把ES6编译成ES5