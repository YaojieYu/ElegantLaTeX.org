---
title: Minimal Example
description : "Minimal Example"
weight: 8
---

Here is a minimal example.

```tex
\documentclass[lang=en]{elegantpaper}

% title information
\title{A Working Paper Example}
\author{ddswhu}
\institute{Elegant\LaTeX{} Group}
\version{1.00}
\date{\today}

\begin{document}

\maketitle

\begin{abstract}
Your abstract goes here.
\keywords{keyword1, keyword2}
\end{abstract}

\section{Introduction}
The content of introduction section.

\section{Conclusion}
The content of conclusion section.
% include the noncited reference

\nocite{ref1, ref2}
\bibliography{wpref}

\end{document}
```
