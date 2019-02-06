---
title: Languages
description : "Languages"
weight: 1
---

I deﬁned one option named `lang`, this option has two alternative values, `lang=en` (default) or `lang=cn` . `lang=cn` will make the caption of ﬁgure/table, abstract name, refname etc. Chinese, while `lang=en` will keep all these
stuff English, as the default article class sets. You can use this option as

```tex
\documentclass[lang=en]{elegantpaper}
\documentclass{en}{elegantpaper} % both ok
```
