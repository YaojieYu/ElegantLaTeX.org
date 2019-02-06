---
title: 插入图片
description : "插入图片"
weight: 5
---

插图的命令和以前一样，也是使用 `figure` 环境。你可以把你的图放到当前工作目录的如下子目录下 ( `./image/` , `./img/` , `./figure/` , `./fig/` )。

```tex
% 如果要使抄录环境显示中文，必须用 XeLaTeX，而不能用 PDFLaTeX
% 这是由于 lstlisting 和 ctex 的问题
\begin{figure}[htbp]
    \centering
    \includegraphics[width=0.6\textwidth]{scatter.pdf}
    \caption{散点图示例\label{fig:scatter}}
\end{figure}
```
