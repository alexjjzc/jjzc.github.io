---
title: JDK安装及配置
date: 2021-07-08 00:00:00
index_img: /img/20.jpg
banner_img: /img/31.jpg
categories: 安装教程
tags: Java
author: 禁忌之城
---
## JDK安装及配置

<!--more-->

### 1.下载

- JDK官网下载地址：

  [ORACLE]: https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html	"ORACLE"
  [OPENJDK]: http://openjdk.java.net/projects/jdk/	"openJDK"

### 2.安装

1.双击安装包进行安装

![](https://gitee.com/lamjjzc/picgo/raw/master/1.png)

2.点击下一步

![](https://gitee.com/lamjjzc/picgo/raw/master/2.png)

3.选择安装位置（可自由选择）

![](https://gitee.com/lamjjzc/picgo/raw/master/3.png)

4.点击“安装”进行安装

![](https://gitee.com/lamjjzc/picgo/raw/master/4.png)

![](https://gitee.com/lamjjzc/picgo/raw/master/5.png)

![](https://gitee.com/lamjjzc/picgo/raw/master/6.png)

### 3.配置

1.在Windows10操作系统中，“我的电脑”右键，选择属性

![](https://gitee.com/lamjjzc/picgo/raw/master/7.png)

2.选择“高级系统设置”

![](https://gitee.com/lamjjzc/picgo/raw/master/8.png)

3.选择“环境变量”

![](https://gitee.com/lamjjzc/picgo/raw/master/9.png)

4.设置“系统变量”，选择“新建”

![](https://gitee.com/lamjjzc/picgo/raw/master/10.png)

- 新建变量：
- 变量名：JAVA_HOME
- 变量值：JDK 根目录
- 变量名：CLASSPATH
- 变量值：.;% JAVA_HOME%\lib\dt.jar;% JAVA_HOME%\lib\tools.jar;

5.设置“Path”

![](https://gitee.com/lamjjzc/picgo/raw/master/11.png)

- 点击新建，输入 % JAVA_HOME%\bin、% JAVA_HOME%\jre\bin
- 点击确定

### 4.验证安装

> “win+R"输入”cmd“打开命令窗口
>
> 输入“java -version"、”java“、”javac“，若出现以下界面即证明安装成功

![](https://gitee.com/lamjjzc/picgo/raw/master/javaversion.png)

![](https://gitee.com/lamjjzc/picgo/raw/master/java.png)

![](https://gitee.com/lamjjzc/picgo/raw/master/javac.png)