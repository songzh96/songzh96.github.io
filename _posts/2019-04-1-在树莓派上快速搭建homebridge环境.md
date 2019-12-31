---
layout:     post
title:      在树莓派上快速搭建homebridge环境
subtitle:   树莓派安装HomeBridge环境
date:       2019-04-1
author:     songzh
header-img: img/post-homebridge.png
catalog: true
tags:
    - HomeBridge
    - Raspberry Pi
---

### 更新系统
`sudo apt-get update`
`sudo apt-get upgrade`

### Nodejs搭建
`sudo apt-get install curl`
`curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -`
`sudo apt-get install -y nodejs`

### 安装homebridge
`sudo apt-get install libavahi-compat-libdnssd-dev`
`sudo npm install -g --unsafe-perm homebridge`

homebridge的文件位置：*C:\Users\ your user name \AppData\Roaming\npm\node_modules*
homebridge的配置文件位置:*C:\Users\your user name\ .homebridge*

homebridge交流群：**107927710**