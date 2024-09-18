Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Definition (The category of groups)
Let $\obj(\mathsf{Grp})$ be the set of all groups.
Now $\forall$ groups $G,H$, let $\hom_{\mathsf{Grp}}(G,H)$ be the set of all group homomorphisms from $G$ to $H$.
Now $\mathsf{Grp}$ is a category if for any $G,H,K\in \obj(\mathsf{Grp}),\varphi:G\to H,\psi:H\to K$, the composition $\psi \circ \varphi:G\to K$ is a group homomorphism.
That is, in the following diagram, 
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\usepackage{amsfonts}
\newcommand\mfbox[1]{\fbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}\newcommand\mmbox[1]{\mbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAHEAdTvAW3gAE7EAF9S6TLnyEUARnJVajFmwAS3PoNWjxIDNjwEiZWYvrNWiDjokHpReaermVV7WNtSjKAEwLnypYgANIaWPxwAsE2epKGMsh+TkoWbNEiijBQAObwRKAAZgBOELxIZCA4EEjyKa4g3PRFaAAWWGERjXTNbSDUDHQARjAMAApx9lZFWNktODHFpeXUVUh+dUG8APrC-UMj43beIAwwBfMeIItliLWriADMAalW2+6612sr1Y-P9V09LB9E77MYTY6nc4LEo3O4-AAsfyC3DQ2A68BR2GBA2GYKOMhA01mFw+MKQT0qPwArEi2JigZdPohEZSkDSNmxttE9rjDl4CUS5tClogKvcWcMwFByRUXEEABT07gAYywRWVANaWAAlOi4IrOKj2pxVerNW1tcKbut7uzJdLEABaB6ywJ0w1ok1qjWcJpa7GgvnxNiCi4UERAA
\begin{tikzcd}
G\times G \arrow[r, "\varphi\times\varphi"'] \arrow[d, "m_G"] \arrow[rr, "(\psi\circ\varphi)\times(\psi\circ\varphi)", bend left] & H\times H \arrow[d, "m_H"] \arrow[r, "\psi\times\psi"'] & K\times K \arrow[d, "m_K"'] \\
G \arrow[r, "\varphi"] \arrow[rr, "\psi\circ\varphi"', bend right] & H \arrow[r, "\psi"] & K \end{tikzcd}
\end{document}
```
the outer rectangle must commute if the two inner rectangles commute.
This is true as $\forall a,b\in G$, we have $(\psi \circ \varphi)(ab)=\psi(\varphi(ab))=\psi(\varphi(a)\varphi(b))=\psi(\varphi(a))\psi(\varphi(b))=(\psi \circ \varphi)(a)\cdot(\psi \circ \varphi)(b)$.