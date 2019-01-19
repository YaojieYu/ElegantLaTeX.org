---
title: 模板选项
description : "本模板的各种选项"
weight: 1
---

## 基础选项

此模板是基于 LaTeX 的标准文档类设计，也即意味着你可以在在文类选项使用文档（article）类型的选项，比如 a4paper, 12pt 等等。本模板支持 PDFLaTeX 和 XeLaTeX 两种编译方式。


## 自定义选项

我在这个模板中定义了一个语言选项 `lang` ，可以选择

+ 英文模式 `lang=en` （默认）;
+ 中文模式 `lang=cn` 

当选择中文模式时，图表的标题引导词以及参考文献，定理引导词等信息会变成中文。你可以通过下面两种方式来选择语言模式：

```tex
\documentclass[lang=cn]{elegantpaper}
\documentclass{cn}{elegantpaper} % 两者皆可
```


