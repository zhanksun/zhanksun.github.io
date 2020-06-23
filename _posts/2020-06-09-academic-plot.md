---
title: 'Make plots in academic papers'
date: 2020-06-09
permalink: /posts/academic-plots/
tags:
  - latex
  - academic
---

This is example plots by $\LaTeX$ package **tikz**.


## Markov Transition Diagram

### Plot

This is a Markov transition diagram for queueing system. 
<img src="/images/ICU.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />


### Codes

```latex
\documentclass{standalone}
\usepackage{tikz}
\usetikzlibrary{automata,positioning,calc}
\usepackage{color}
\definecolor{gray97}{gray}{.97}
\definecolor{gray75}{gray}{.75}
\definecolor{gray45}{gray}{.45}
\begin{document}

    \begin{tikzpicture}[font=\sffamily\small]
        
        % Add states for those in service
        \node[state,
              text=black,
              draw=blue] (s1) {1};
        \node[draw=none, below=.6cm of s1]   (s1exit)   {$p_{10}$};
        \node[state,
              right=1.5cm of s1,
              text=black, 
              draw=blue, 
              fill=none] (s2) {2};
        \node[draw=none, below=.6cm of s2]   (s2exit)   {$p_{20}$};
              
        % Connect the states with arrows
        \draw[every loop,
        auto=none,
        line width=.2mm,
        >=latex,
        draw=black,
        fill=none]
            (s1) edge[bend left, auto=left]  node {$p_{10}$} (s2)
            (s1) edge node {} (s1exit)
            (s2) edge node {} (s2exit)
            (s2) edge[bend left, auto=left] node {$p_{21}$} (s1)
            (s1) edge[loop left]             node {$p_{11}$} (s1)
            (s2) edge[loop right]             node {$p_{22}$} (s2);
        \draw[black] ($(s1)+(-1.7,-1.5)$) rectangle (4.1,1.5) node[xshift=-5.2cm,yshift=-.3cm]{Service};
       
       % Add states for those waiting in queue
        \node[state,
              right=2.5cm of s2,
              text=black, 
              draw=black, 
              fill=gray75] (q1) {1};
        \node[draw=none, below=.6cm of q1]   (q1exit)   {$q_{10}$};
        \node[state,
              right=1.5cm of q1,
              text=black, 
              draw=black, 
              fill=gray75] (q2) {2};
        \node[draw=none, below=.6cm of q2]   (q2exit)   {$q_{20}$};
        
        % Connect the states with arrows
        \draw[every loop,
        auto=none,
        line width=.2mm,
        >=latex,
        draw=black,
        fill=none]
            (q1) edge[bend left, auto=left]  node {$q_{10}$} (q2)
            (q1) edge node {} (q1exit)
            (q2) edge node {} (q2exit)
            (q2) edge[bend left, auto=left] node {$q_{21}$} (q1)
            (q1) edge[loop left]             node {$q_{11}$} (q1)
            (q2) edge[loop right]             node {$q_{22}$} (q2);
        \draw[black] ($(q1)+(4.2,-1.5)$) rectangle (4.1,1.5) node[xshift=.6cm,yshift=-.3cm]{Queue};
    \end{tikzpicture}

\end{document}
```


## ED Patient Flow 