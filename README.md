# Library Develop Cli

- 该库作为自定义扩展开发工具，用于链平台追踪的拓扑图树

## Getting started
开发组件库
```
cd template-project
npm install
npm run dev
```
## Production
```
|-lib
  |-index.ts // 库入口文件，打包自动生成
|-packages
  |-index.ts // 库源码入口文件
|-src // 开发调试目录
  |-App.vue // 开发页面
  |-main.ts // 开发项目入口文件
|-package.json // 项目依赖以及包入口配置文件
|-vite.config.ts // 项目开发环境启动vite配置文件
|-vite.lib.config.ts // 项目库源码打包环境vite配置文件，打包命令：npm run lib
```
## How to use
### 第1步
开发npm库...
### 第2部
打包源码
```
npm run lib
```
### 第3部
发布
```
npm login
npm publish
```