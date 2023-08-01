---
title: 'Mac上安装多版本node'
description: '开发旧项目时，使用低版本Nodejs。开发新项目时，需使用高版本Node.js。

可同时安装多个版本Node.js，并切换到指定版本Node.js。'
pubDate: 'Aug 01 2023'
heroImage: '/blog-placeholder-3.jpg'
---

##### 1、全局安装
`npm install -g n`

##### 2、安装指定node版本
比如我的电脑上安装了一个 16.13.2的和一个18.16.0的  
`sudo -E n 18.16.0`

##### 3、查看已安装的版本列表
`n list`

##### 4、删除指定版本
`n rm 16.13.2`

##### 5、切换node版本
`sudo n`

##### 6、查看切换版本
`node -v`   
`npm -v`