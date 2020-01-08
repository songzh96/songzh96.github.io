---
layout:     post
title:      Win10快速搭建Homebridge环境
subtitle:   WIN10安装HomeBridge环境
date:       2019-05-18
author:     songzh
header-img: img/post-homebridge.png
catalog: true
tags:
    - HomeBridge
    - WIN10
---

### 1.安装nodejs
这些Windows安装说明已经过v8.xx系列节点的测试，因此建议您使用该系列或更高版本的版本。早期版本的NodeJS可能有效，但尚未经过测试。

你可以在这里下载：[nodejs](https://nodejs.org/)

![nodejs](https://upload-images.jianshu.io/upload_images/3246153-024d3bc3be52844f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**我使用的是10.15.3版本，亲测可用**
安装完以后，打开一个cmd窗口进行测试。
**查看node版本**
`node -v`
**查看npm版本**
`npm -v`

![查看node版本](https://upload-images.jianshu.io/upload_images/3246153-00f71dcc5506a55a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 2.安装homebridge
在CMD窗口中输入以下命令
` npm install -g homebridge`

### 3.测试homebridge
安装完成后，你可以在CMD窗口中输入以下命令
`homebridge`
如果你运行后的结果和下图一样，那么恭喜你，你已经安装完成了。

![运行成功的界面](https://upload-images.jianshu.io/upload_images/3246153-706d1f6bc9375ca9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 4.其他
homebridge的文件位置：*C:\Users\ your user name \AppData\Roaming\npm\node_modules*
homebridge的配置文件位置:*C:\Users\your user name\ .homebridge*

homebridge交流群：**107927710**