---
title: Hexo使用方法
date: 2017-10-18 21:05:27
update: 2017-10-20 20:02:18
tags: Hexo
categories: Skill
comments: true
thumbnail: https://mir-s3-cdn-cf.behance.net/project_modules/1400/801a7049008983.58a83de93d03d.jpg
---
![](https://mir-s3-cdn-cf.behance.net/project_modules/1400/08f1a457579679.59dcfd1608c9f.png)
由于机缘巧合，最近上网看到一个博主的个人博客网站，它非常好。引起我也想搭建一个网站的兴趣。对网站有些许了解的我最终找到这个网站的核心：hexo框架。
经过不断的煎熬，我也终于搭建完成属于我自己的个人博客，博客地址：jiluolao.xyz
下面是我对hexo在 Windows电脑上 搭建方法的总结，写的不好还请见谅，欢迎大家指正修改。

## 什么是hexo？
Hexo 是一个快速、简洁且高效的博客框架。Hexo 使用 Markdown（或其他渲染引擎）解析文章，在几秒内，即可利用靓丽的主题生成静态网页。

## 安装前提
安装 Hexo 相当简单。然而在安装前，您必须检查电脑中是否已安装下列应用程序：
- Node.js
- Git
如果您的电脑中已经安装上述必备程序，那么恭喜您！接下来只需要使用 npm 即可完成 Hexo 的安装。（这里我的是直接用电脑的cmd命令提示符安装hexo的，因为我已经安装上述两个程序，但是npm单独打不开，所有不得已而为之）

## Node.js和Git的安装方法
Node.js官网链接：[点击](http://nodejs.cn/)
Git官网链接：[点击](https://git-scm.com/)

## 安装 Hexo
所有必备的应用程序安装完成后，即可使用 npm 安装 Hexo。可以在电脑桌面点击右键弹窗中选择Git Bash Here
然后在弹窗中输入以下代码：
``` bash
$ npm install -g hexo-cli （$不用写，前面本来就有，没有也不用写，以后的也是。注意空格）
```
按回车键，然后等待。。。
测试看看有木有更新。。。