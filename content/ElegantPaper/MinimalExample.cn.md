---
title: 最小示例
description : "最小示例"
weight: 8
---

在这部分，我提供一个示例文档：

```tex
\documentclass[lang=cn]{elegantpaper}

% 标题信息
\title{工作论文示例展示}
\author{ddswhu}
\institute{Elegant\LaTeX{} 项目组}
\version{1.00}
\date{\today}

\begin{document}

\maketitle

\begin{abstract}
在这里写摘要。
\keywords{关键词1，关键词2}
\end{abstract}

\section{引言}
这一部分是引言的内容。

\section{结论}
这是结论部分。
% 在参考文献部分显示未引用的文献

\nocite{ref1, ref2}

% 生成参考文献
\bibliography{wpref}

\end{document}
```
