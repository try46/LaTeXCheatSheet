# LaTeXCheatSheet

## ご自由にご使用ください(何かあっても自己責任でお願いします)

## よく使うと思われるテンプレ1(ソースコード挿入なし)

```tex
\documentclass[a4j]{jarticle}
\usepackage[dvipdfmx]{graphicx}
\usepackage{here}
\usepackage{url}
\begin{document}
\end{document}
```

## よく使うと思われるテンプレ1(ソースコード挿入あり)
```
\documentclass[a4j]{jsarticle}
\usepackage{fancybox}
\usepackage{amssymb, amsmath}
\usepackage{listings,jlisting}
\usepackage[normalem]{ulem}
\usepackage{ascmac}
\usepackage[table,xcdraw]{xcolor}
\usepackage{comment}
\usepackage{here}
\usepackage{url}
\useunder{\uline}{\ul}{}
\lstset{
	language={Java},
	language={HTML},
basicstyle={\ttfamily\scriptsize},
  breaklines={true},
  commentstyle={\textit},
  classoffset={1},
  keywordstyle={\bfseries},
  frame={single},
  framesep={5pt},
  showstringspaces={false},
  numbers={left},
  stepnumber={1},
  numberstyle={\tiny},
  tabsize={2}
}
\usepackage[dvipdfmx]{graphicx}
\begin{document}
\end{document}
```


