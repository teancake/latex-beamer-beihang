This is an UNOFFICIAL beamer style for Beihang University. The following is an example of how it is used.

\documentclass[10pt]{beamer}

\ifx\pdfoutput\undefined
% we are running LaTeX, not pdflatex
\usepackage{graphicx}
\else
% we are running pdflatex, so convert .eps files to .pdf
\usepackage{graphicx}
\usepackage{epstopdf}
\fi

\input{beihangbeamerstyle/beihangcolor}
\input{beihangbeamerstyle/beihangbeamerstyle}

\title{Beamer Style of Beihang University}
\author{Xiaoke Yang\\
Beihang University (\texttt{xiaokeyang@buaa.edu.cn})}
\date{Wed  1 Jun 11:25:45 CST 2016}


\begin{document}
%----------------------------------------------------------------------
% Title frame
\begin{frame}[plain]
\maketitle
\end{frame}

%----------------------------------------------------------------------
% Content frame
\begin{frame}
\frametitle{Motivation}
\framesubtitle{Why I made this beamer style}
\end{frame}
\end{document}


Do not change the name of the folder, as it is used in the tex files.

Xiaoke Yang <das.xiaoke@hotmail.com>
Wed  1 Jun 11:25:45 CST 2016

