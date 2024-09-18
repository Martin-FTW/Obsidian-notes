Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Definition II.3.1 (Group homomorphism)
Let $G,H$ be groups and $\varphi:G\to H$.
Denote $m_{G}:G\times G\to G$ and $m_{H}:H\times H\to H$ their multiplication maps.
We call $\varphi$ a group homomorphism if $m_{H}\circ (\varphi \times \varphi)=\varphi \circ m_{G}$, i.e. the following diagram commutes
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\usepackage{amsfonts}
\newcommand\mfbox[1]{\fbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}\newcommand\mmbox[1]{\mbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAHEAdTvAW3gAE7EAF9S6TLnyEUARnJVajFmwAS3PoNWjxIDNjwEiZWYvrNWiDjokHpReaermVV7SMUwoAc3hFQAGYAThC8SGQgOBBI8koWbNz0QWgAFlgaWPxwiXTJaTYgwaHh1FFIAEzOypYgvAD6wtQMdABGMAwACpKGMiBBWN4pOAVFYYixZYgAzFXxVvXuuqMVpdHTs64gOXlYIE2t7V12Rlb9g8MeIkA
\begin{tikzcd}
G\times G \arrow[r, "\varphi\times\varphi"] \arrow[d, "m_G"'] & H\times H \arrow[d, "m_H"] \\
G \arrow[r, "\varphi"'] & H \end{tikzcd}
\end{document}
```
That is, $\varphi(ab)=\varphi(a)\varphi(b)$ for all $a,b\in G$.