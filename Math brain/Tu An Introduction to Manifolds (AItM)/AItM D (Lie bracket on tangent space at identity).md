Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Lie bracket on tangent space at identity)
Let $G$ be a Lie group.
Denote by $\varphi:T_{e}G\iso L(G)$ the correspondence in [[AItM D (Left-invariant vector field)]].
Define $\lie{A}{B}\coloneqq \varphi ^{-1}(\lie{\varphi(A)}{\varphi(B)})=\lie{\tilde{A}}{\tilde{B}}_{e}$ for all $A,B\in T_{e}G$.
Then we have a Lie bracket on $T_{e}G$.
This Lie bracket is induced by the natural Lie bracket of vector fields in the subalgebra $L(G)$ of $\mathfrak{X}(G)$ and the isomorphism $\varphi:T_{e}G\iso L(G)$ in [[AItM D (Left-invariant vector field)]], by mapping according to the diagram
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\usepackage{amsfonts}
\newcommand\mfbox[1]{\fbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}\newcommand\mmbox[1]{\mbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRABUB9GAAgHEAOgLwBbeDy68+IAL6l0mXPkIoyARiq1GLNgBkAFHwCUQ0eIPHZ8kBmx4CRNeU31mrRB278rCu8sekGtSuOh4WRrKaMFAA5vBEoABmAE4QIkhkIDgQSE5abmxC9MloABZYplhicEV0JeU+IClpudTZSADMwdruIMhCAMZQEDikg8M4FI3N6YhdWTmIAEzdBR619VgAesAAtGoy06mzme3L1AxYYL1QdHCl0ZEyQA
\begin{tikzcd}
T_e G\times T_e G \arrow[d, "\varphi\times\varphi"] \arrow[r, dashed] & T_e G \\
L(G)\times L(G) \arrow[r, "{[\cdot,\cdot]}"] & L(G) \arrow[u, "\varphi^{-1}"]
\end{tikzcd}
\end{document}
```