reference web: https://oi-wiki.org/tools/latex/
Using chinese: 
                \documentclass[a4paper,12pt]{article}
                \usepackage{amsmath}
                *\usepackage{CJKutf8}*

                \begin{document}

                \title{Linearized Simple Land-Surface Parameterization Scheme}
                \author{Xinyi Yang}
                \date{\today}
                \maketitle

                \pagenumbering{roman}
                \tableofcontents
                \newpage
                \pagenumbering{arabic}

                \section{Introduction}
                This is the introduction.

                \begin{CJK}{UTF8}{gbsn}

                你好啊啦啦啦
                \end{CJK}

                \section{Methods}

                \subsection{Stage 1}
                \label{sec1}
                The first part of the methods.

                \section{Results}
                Here are my results. Referring to section \ref{sec1} on page \pageref{sec1}

                \end{document}
