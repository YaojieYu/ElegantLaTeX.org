---
title: Graphics
description : "Graphics"
weight: 5
---

To include a graphic, you can use `ﬁgure` environment as usual. You can put all
your images in the sub directories ( `./image/` , `./img/` , `./ﬁgure/` , `./ﬁg/` ) of your current working directory.

```tex
\begin{figure}[htbp]
    \centering
    \includegraphics[width=0.6\textwidth]{scatter.pdf}
    \caption{Scatter Plot Example \label{fig:scatter}}
\end{figure}
```
