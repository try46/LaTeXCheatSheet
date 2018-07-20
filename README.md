# LaTeXCheatSheet

## ご自由にご使用ください(何かあっても自己責任でお願いします)<br>パッケージについては一部自分で追加している物もありますその場合は自分の環境に合わせるか適宜追加をお願いします。

## よく使うと思われるテンプレ1(ソースコード挿入なし)

```tex
\documentclass[a4j]{jarticle}
\usepackage[dvipdfmx]{graphicx}
\usepackage{here}
\usepackage{url}
\begin{document}
\end{document}
```

## よく使うと思われるテンプレ2(ソースコード挿入あり)
```tex
\documentclass[a4j]{jsarticle}
\usepackage{fancybox}
\usepackage{amssymb, amsmath}
\usepackage{listings,jlisting}
\usepackage[normalem]{ulem}
\usepackage{eclclass}%このスタイルシートは自分で追加
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

## 部、章、節、小節、少々節
```tex
\part{hoge}%部、第Ⅰ部hoge
\chapter{hoge}%章 第1章hoge
\section{hoge}%節 1.hoge
\subsection{hoge}%小節 1.1 hoge
\subsubsection{hoge}%少々節 1.1.1 hoge
```
章に関しては`jreport.sty`、`jbook.sty`を使用しているときのみ。

## 表について
```tex
\begin{table}[htbp]
\centering
\caption{test}
\begin{tabular}{|c|c|c|c|c|}
月&火&水&木&金\\ \hline
国語&数学&理科&社会&道徳\\ \hline
\end{tabular}
\label{時間割}
\end{table}
```
結果:↓

|  月  |  火  |  水  |  木  |  金  |
|:----:|:----:|:----:|:----:|:----:|
| 国語 | 数学 | 理科 | 社会 | 道徳 |
