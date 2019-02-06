---
title: 插入表格
description : "插入表格"
weight: 6
---

我强烈建议你使用 `booktabs` 宏包，这个宏包有三个命令 `\toprule`、`\midrule` 和 `\bottomrule` 能方便你制作三线表。下面是一个示例：

```tex
\begin{table}[htbp]
    \small
    \centering
    \caption{燃油效率与汽⻋价格}
    \begin{tabular}{lcc}
    \toprule
    & (1)        & (2)         \\
    \midrule
    燃油效率      & -238.90*** & -49.51 \\
    & (53.08)   & (86.16) \\
    汽车重量      &            & 1.75*** \\
    &           & (0.641)     \\
    常数项       & 11,253***  & 1,946 \\
    & (1,171)   & (3,597)     \\
    观测数       & 74         & 74 \\
    $R^2$       & 0.220      & 0.293 \\
    \bottomrule
    \multicolumn{3}{l}{\scriptsize 括号内为标准误} \\
    \multicolumn{3}{l}{\scriptsize *** p<0.01, ** p<0.05, * p<0.1} \\
    \end{tabular}%
    \label{tab:reg}%
\end{table}%
```
