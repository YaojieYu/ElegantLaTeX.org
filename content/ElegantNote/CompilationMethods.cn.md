---
title: 编译方式
description : "编译方式"
weight: 5
---

本模板支持两种编译方式，`PDFLaTeX` 和 `XeLaTeX`。

+ 选用 `PDFLaTeX` 编译的话，如果用到了中文，则会调用 `ctex` 宏包；
+ 选用 `XeLaTeX` 编译的话，则会调用 `xeCJK` 宏包。

模板测试环境为 Win10 + TEX Live 2018，设定的字体为 Windows 中的宋体、楷体、黑体、微软雅黑等。如果你的电脑是 Mac/Linux 系统，而且采用 `XeLaTeX` 编译的话，请把 elegantnote.cls 中字体改为自己系统的字体。
