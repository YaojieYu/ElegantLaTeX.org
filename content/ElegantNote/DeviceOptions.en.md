---
title: Device Options
description : "Device Options"
weight: 2
---

To make the notes more comfortable to read, we designed four output options (of different sizes) that correspond to different reading devices: Pad, Kindle, PC and A4paper. The options of output for different devices are

```tex
\documentclass[device=pad]{elegantnote}
\documentclass[device=kindle]{elegantnote}
\documentclass[device=pc]{elegantnote}
\documentclass[device=normal]{elegantnote}
```

__Note:__ You can also select the device by using a direct assignment method, such as:

```tex
\documentclass[pad]{elegantnote}
\documentclass[kindle]{elegantnote}
\documentclass[pc]{elegantnote}
\documentclass[normal]{elegantnote}
```

Note that if you want a normal A4paper size PDF, you need to select `device=normal` instead of `device=pc` , because `device=pc` is actually set to double page mode on your computer.
