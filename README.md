# 微信小程序 — “Cmusic”音乐项目

## 1. 项目概述

- 本项目是基于原生微信小程序开发的模仿“网易云”音乐项目
- 主要的功能模块有：主页，视频页，个人中心，推荐歌曲页， 音乐播放页等
- 前台用原生小程序API 写的，页面采用 flex 布局，并且用 npm 模块引入第三方库
- 后台用node写的，后台接口也是网易云提供的真实接口，实时更新数据

## 2. 技术选型

- wxml 语法 + x.showToast + wx.navigateTo + wx.request + wx.setStorage 等多种API
- npm 引入 pubsub-js 

## 3. 项目启动

```
先启动后端项目
cd Cmusic_server
npm install 
npm start
再启动前端项目,用微信开发者程序编译即可
```

## 4. 项目预览

主页

![image] (/imgs/1.jpg)

