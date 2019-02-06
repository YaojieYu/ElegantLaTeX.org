---
title: 语言模式
description : "语言模式"
weight: 1
---

我在这个模板中定义了一个语言选项 `lang`，可以选择英文模式 `lang=en`（默认）或者中文模式
`lang=cn`。当选择中文模式时，图表的标题引导词以及参考文献，定理引导词等信息会变成中文。你
可以通过下面两种方式来选择语言模式：

```tex
\documentclass[lang=cn]{elegantpaper}
\documentclass{cn}{elegantpaper} % 两者皆可
```
