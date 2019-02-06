---
title: Font Settings
description : "Font Settings"
weight: 2
---

##  Compile with `PDFLaTeX`

If you choose `PDFLaTeX` to process your paper, the default article font computer modern has changed to `newtx` series, and the default font size is set to `11pt` . The fonts are settings with:

+ `newtxtext` package for text fonts, similar to times new roman font.
+ `newtxmath` package for math fonts, close to `times` package.
+ `FiraMono` package for typewriter fonts, with option `scale=0.8` .
+ `ctex` package for Chinese fonts, with option `scheme=plain` .

## Compile with `XeLaTeX`

If you choose `XeLaTeX` to process your paper, I use `fontspec` package and `xeCJK` package. I used fonts available in Windows, if you are using Linux or Mac OS, please substitute these fonts with that of your system. The font setting part

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
\XeTeXlinebreaklocale "zh"
\XeTeXlinebreakskip = 0pt plus 1pt minus 0.1pt
\RequirePackage{newtxmath}
```

## Other Settings

These packages operate perfectly but are inappropriate for big operators, for example  `\sum` and `\prod`, thus, I change these operators back to computer modern font. 

The `\linespread` (controls line spacing) is set to 1.3, and I use `microtype` to improve the font justiﬁcation. `type1cm` package is used to remove the font shape and font size warning messages.
