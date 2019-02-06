---
title: 字体设置
description : "字体设置"
weight: 2
---

本模板支持两种编译方式，`PDFLaTeX` 和 `XeLaTeX`。

##  选择 `PDFLaTeX` 编译

如果你使用 `PDFLaTeX` 编译，默认的 Computer Modern 字体被换成了 `newtx` 系列字体，默认的字体字号是 11 pt。关于字体设置的宏包主要用到了：

+ `newtxtext` 用于文档正文字体，类似于 Times New Roman 字体。
+ `newtxmath` 用于数学字体，搭配 `newtx` 非常合适，类似于过时的 `times` 宏包的效果。
+ `FiraMono` 用于打字机字体，并使用了 `scale=0.8` 选项。
+ `ctex` 用于中文字体设置，并使用了 `scheme=plain` 选项。

## 选择 `XeLaTeX` 编译

如果你选择 `XeLaTeX` 编译的话，那么设置字体的宏包为 `fontspec` 和 `xeCJK`。由于模板中使用的字体是 Windows 中的字体，所以如果你使用其他操作系统，比如 Linux 或者 Mac OS，那么你需要把所用字体替换为你系统中的字体。设置字体的命令：

```tex
\RequirePackage{fontenc}
\RequirePackage[no-math]{fontspec}
\setmainfont{Times New Roman}[NFSSFamily=ntxtlf]
\setsansfont{Arial}
%\setmonofont[Scale=0.9]{Courier New}
\RequirePackage{xeCJK}
\RequirePackage{xunicode}
\setCJKmainfont[BoldFont={SimHei},ItalicFont={KaiTi}]{SimSun}
\setCJKsansfont[BoldFont={SimHei},ItalicFont={KaiTi}]{KaiTi}
\setCJKmonofont[BoldFont={SimHei},ItalicFont={KaiTi},Scale=0.9]{Microsoft YaHei}
\XeTeXlinebreaklocale ”zh”
\XeTeXlinebreakskip = 0pt plus 1pt minus 0.1pt
\RequirePackage{newtxmath}
```

这几个包由于都是一个系列的，字体搭配起来非常合适，字体宽度非常契合！唯独数学字体中的大型运算符，比如求和符号和积分符号不是很好看，为此，我把它们又改回了原先的字体效果。

我把行距设定为 1.3，并且使用了 `microtype` 宏包调整字体的间距，为了去除字体字号，字形警告信息，我使用了 `type1cm` 宏包。

