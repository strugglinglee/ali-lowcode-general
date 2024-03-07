# 综合场景

## src/index.ts
1. 通过 plugins.register 注册各种插件，包括官方插件 (已发布 npm 包形式的插件) 和 plugins 目录下内置的示例插件
2. 通过 init 初始化低代码设计器

## plugins
存放示例插件

## services 
模拟数据请求、提供默认 schema、默认资产包等，此目录下内容在真实项目中应替换成真实的与服务端交互的服务

## preview.tsx
预览页面入口