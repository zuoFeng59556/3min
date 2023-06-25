---
title: "30 秒拥有自己的 ChatGPT（一行代码不用写）"
subtitle: ""
date: 2023-06-15
lastmod: 2023-06-15
author: "左风"
authorLink: ""

tags: [项目]
categories: [Sealos 教程]
---

> 先上效果图

![](./image/1.png)

话不多说直接开整！

## 预备条件

- 有一台能打开浏览器的电脑
- 有一个 ChatGPT 的 Key

> 如果你没有我送你一个
> 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

## 开始

浏览器打开这个网址 https://sealos.io/ 点击 **在线使用** 然后登陆进来。

点这个 **AppLaunchpad** 
![](./image/2.jpeg)

点右上新建
![](./image/3.png)


这个页面里需要输入的东西有：
> 文末会解释为什么填写这些，现在我们先快速搭建起来
- AppName 这个随便起个名字就可以
- Image Name 填写 yidadaa/chatgpt-next-web
- CPU 选择 1
- Memory 选择 521Mi
- Container Ports 填写 3000
- Accessible to the Public 这个点击打开

填写完这些后点击右上角 **Deploy Application**
![](./image/4.png)


到这个页面点击这个链接访问大功告成
> 如果访问不了就稍微等一会，可能是还没部署成功

![](./image/6.png)


打开之后在这里填入 ChatGPT 的 Key

![](./image/5.png)

ok 搞定！


## 干了什么？
- Image Name 填写 yidadaa/chatgpt-next-web ，这一步是写了一个开源项目作者提供的镜像名，这里不多做解释，如果你遇到一个项目开源并且提供的容器的部署方式（就是能找到镜像名）都可以用这种方式一建部署。   

- CPU 选择 1 Memory 选择 521Mi ，这里是我测试的最低能跑这个项目的配置，如果给的低了项目跑不起来。   

- Container Ports 填写 3000 ，这里是项目作者暴露的端口，一般都会写在部署文档上，写什么填什么就好了。  

- Sealos收费问题：新用户注册会送五块钱，部署这个项目大概能跑个几天，后面想继续用的话就要充钱了。

## 联系我
备注 ChatGPT 拉你进群。