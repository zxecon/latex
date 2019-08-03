For most Ph.D. students in economics, latex is the most widely used document preparation system. This note provide one technique in preparing tables. The packages we need are as follows:
```tex
\usepackage{textcomp,booktabs}
\usepackage[usenames,dvipsnames]{color}
\usepackage{colortbl}
```
Along with the following settings:
```tex
\definecolor{Gray}{gray}{0.9}
\definecolor{bl}{cmyk}{.3,0,0,0}
```
These settings gives you ways to create your own color bases.

Sample table:

- row color
```tex
\begin{table}[]
\begin{center}
\caption{Test}
\label{test}
\begin{tabular}{c|cccccc}
 & \multicolumn{6}{c}{MM} \\ \hline
 Title &      G     &  H    &I &J &K& L\\ \hline
 \rowcolor{Gray}
 A&        21.86 &   21.7    & 6.4      &        21.86 &   21.7    & 6.4\\ \hline
 B&           21.55   & 21.41  &   10.9   &        21.86 &   21.7    & 6.4\\ \hline
 \rowcolor{Gray}
C&          19.58 &  19.4    &  12.0       &        21.86 &   21.7    & 6.4\\ \hline
 D&         1.38   & 1.96   &  -2.3    &        21.86 &   21.7    & 6.4\\ \hline
 \rowcolor{Gray}
 E&         1.85  &   2.43    &  -8.2  &        21.86 &   21.7    & 6.4\\ \hline
F&         48.74  &  63.8    &  -9.7  &        21.86 &   21.7    & 6.4 \\ \hline  
\hline
\end{tabular}
\end{center}
\end{table}
```

Showed as follows:

![table1](https://github.com/zxecon/note/blob/master/t1.png)

- number highlighting
```tex
\begin{table}[]
\begin{center}
\caption{Test}
\label{test}
\begin{tabular}{c|cccccc}
 & \multicolumn{6}{c}{MM} \\ \hline
 Title &      G     &  H    &I &J &K& L\\ \hline
 \rowcolor{Gray}
 A&        21.86 &   21.7    & 6.4      &        21.86 &   21.7    & 6.4\\ \hline
 B&           21.55   &  \multicolumn{1}{>{\columncolor{bl}}c}{21.41}  &   10.9   &        21.86 &   21.7    & 6.4\\ \hline
 \rowcolor{Gray}
C&          19.58 &  19.4    &  12.0       &        21.86 &   21.7    & 6.4\\ \hline
 D&          \multicolumn{1}{>{\columncolor{bl}}c}{1.38}  & 1.96   &  -2.3    &        21.86 &   21.7    &  6.4\\ \hline
 \rowcolor{Gray}
 E&         1.85  &    2.43    &  -8.2  &        21.86 &   21.7    & 6.4\\ \hline
F&         48.74  &  63.8    &  -9.7  &        21.86 &   21.7    & 6.4 \\ \hline  
\hline
\end{tabular}
\end{center}
\end{table}
```

Showed as follows:

![table2](https://github.com/zxecon/note/blob/master/t2.png)

- colunm highlighting
```tex
\begin{table}[]
\begin{center}
\caption{Test}
\label{test}
\begin{tabular}{c|ccccc >{\columncolor{yellow}}c}
 & \multicolumn{6}{c}{MM} \\ \hline
 Title &      G     &  H    &I &J &K& L\\ \hline
 A&        21.86 &   21.7    & 6.4      &        21.86 &   21.7    & 6.4\\ \hline
 B&           21.55   &  \multicolumn{1}{>{\columncolor{bl}}c}{21.41}  &   10.9   &        21.86 &   21.7    & 6.4\\ \hline
C&          19.58 &  19.4    &  12.0       &        21.86 &   21.7    & 6.4\\ \hline
 D&          \multicolumn{1}{>{\columncolor{bl}}c}{1.38}  & 1.96   &  -2.3    &        21.86 &   21.7    &  6.4\\ \hline
 E&         1.85  &    2.43    &  -8.2  &        21.86 &   21.7    & 6.4\\ \hline
F&         48.74  &  63.8    &  -9.7  &        21.86 &   21.7    & 6.4 \\ \hline  
\hline
\end{tabular}
\end{center}
\end{table}
```

Showed as follows:

![table3](https://github.com/zxecon/note/blob/master/t3.png)
