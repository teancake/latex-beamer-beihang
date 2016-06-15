An Unofficial LaTeX beamer style for Beihang University
=======================================================


**NOTE**

1. This is an UNOFFICIAL LaTeX beamer style for Beihang University.
2. This is not exactly a beamer style, rather it contains two LaTeX files to be inserted in the slides' source file.
3. Do not change the name of the folder "beihangbeamerstyle", as it is used in the tex files.
4. These files are based on Edward Hartley's work <http://www-control.eng.cam.ac.uk/Main/EdwardHartley>.
5. Complaints or suggestions are always welcome.

An Example
----------
The following is simple example of how it is used.

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

A more complete example is provided in the example.tex file.

Xiaoke Yang <das.xiaoke@hotmail.com>
Wed  1 Jun 11:25:45 CST 2016

