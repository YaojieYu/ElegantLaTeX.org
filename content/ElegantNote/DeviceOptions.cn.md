---
title: 设备选择
description : "设备选择"
weight: 2
---

为了让笔记方便在不同设备上阅读，免去切边，缩放等操作，本模板适配不同的屏幕大小，分别为 Pad，Kindle，PC，A4。不同屏幕的选择为

```tex
\documentclass[device=pad]{elegantnote}
\documentclass[device=kindle]{elegantnote}
\documentclass[device=pc]{elegantnote}
\documentclass[device=normal]{elegantnote}
```

__注：__ 也可以采取直接赋值的方法选择屏幕，比如：

```tex
\documentclass[pad]{elegantnote}
\documentclass[kindle]{elegantnote}
\documentclass[pc]{elegantnote}
\documentclass[normal]{elegantnote}
```

__注：__ 如果想要得到普通的 A4 纸张大小的 PDF，需要选择 `device=normal`，而不是选择 `device=pc`，因为 `device=pc` 实际上设置的是电脑双页模式。
