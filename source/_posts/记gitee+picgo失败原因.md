---
title: 记Gitee+PicGo失败原因
date: 2022-05-29 11:20:03
index_img: /img/45.jpg
banner_img: /img/41.jpg
categories: Recode
tags: Gitee PicGo
author: 禁忌之城
---
记gitee+picgo失败原因

<!--more-->

## 1.原因

### Create a new post

许久未使用picgo了，今天打开picgo，发现需要更新正式版，期待这个正式版很久了！！！

快速更新之后，试图往gitee上传图片，发现进度条结束后，gitee中并没有上传的图片，picgo中的相册里也没有，最关键的是picgo尽然没有任何报错信息！

无奈之余，开始了百度之旅..................................按照百度的各种方法实验后均没有效果，图片依然无法上传，我决定去picgo找原因，在“日志文件”中，我发现了其中的猫腻，看图：

![](https://raw.githubusercontent.com/lamborcola/image/main/picgo%E6%8A%A5%E9%94%99%E4%BF%A1%E6%81%AF.jpg)

**图中的403即：HTTP 403 Forbidden 是“拒绝访问”，出现403表示服务器接收到了本次的请求，但是拒绝响应，拒绝执行该任务！**

尝试更换了Token，依然是同样的报错信息；

更换gitee账号，再次上传，同样的报错信息；

安装所有gitee相关的插件，依旧出错；

个人猜测，gitee对picgo的上传作出了限制；

### 2.解决方案

目前来看，这个问题误解，可以更换图床，或者自己搭建一个。
