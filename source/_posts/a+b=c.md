---
title: a+b=c
date: 2021-06-05 09:08:03
index_img: /img/3.jpg
banner_img: /img/3.jpg
categories: Code
tags: Java Python
author: 禁忌之城
---
## a+b=c

<!--more-->

### JAVA解析

``` java
import java.util.*;
public class test1 {
    public static void main(String args[]){
        int A=0,B=0,C=0,D=0;
        System.out.println("A:");
        System.out.println("B:");
        System.out.println("C:");
        Scanner data = new Scanner(System.in);
        A=data.nextInt();
        B=data.nextInt();
        D=data.nextInt();
        C=A+B;
        if(D!=C){
            System.out.println("抱歉，你算错了");
        }else{
            System.out.println("恭喜你答对了");
        }
    }
}
```

### Python解析

``` python
a=int(input("请输入a:"));
b=int(input("请输入b:"));
c=int(input("请输入c:"));
sum=a+b;
if(sum!=c):
    print("抱歉，你算错了");
else:
    print("恭喜你答对了");xxxxxxxxxx a=int(input("请输入a:"));b=int(input("请输入b:"));c=int(input("请输入c:"));sum=a+b;if(sum!=c):    print("抱歉，你算错了");else:    print("恭喜你答对了");$ hexo serverbash
```
