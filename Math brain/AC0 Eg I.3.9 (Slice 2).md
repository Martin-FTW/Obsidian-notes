Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Example I.3.9 (Slice 2)
Let $\mathsf{C}$ be a category and $A,B\in \obj(\mathsf{C})$.
Define $\mathsf{C}_{A,B}$ by
- $\obj(\mathsf{C}_{A,B})=\set{(f,g,Z)\given Z\in \obj \mathsf{C},f\in\hom(Z,A),g\in \hom(Z,B))}$, i.e. every object is a diagram in $\mathsf{C}$: 
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBoBGAXVJADcBDAGwFcYkQAtEAX1PU1z5CKcqWLU6TVuwCCPPiAzY8BIqIBMEhizaIQAIR4SYUAObwioAGYAnCAFskZEDghJRkneyvzrdx4jOrkjqNNrSeqZG3EA
\begin{tikzcd} & A \\
Z \arrow[ru, "f"] \arrow[rd, "g"] & \\ & B
\end{tikzcd}
\end{document}
```
- $\forall$ objects $(f_{1},g_{1},Z_{1}),(f_{2},g_{2},Z_{2})$, $\hom_{\mathsf{C}_{A}}((f_{1},g_{1},Z_{1}),(f_{2},g_{2},Z_{2}))=\set{\sigma\in \hom_{\mathsf{C}}(Z_{1},Z_{2})\given f_{1}=f_{2}\sigma,g_{1}=g_{2}\sigma}$, i.e. the set of all morphisms $\sigma$ that makes the following diagram commute: 
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZARgBpiBdUkANwEMAbAVxiRAC0B9AJhAF9S6TLnyEU3UgAYqtRizYBBfoJAZseAkQncZ9Zq0QgAQsqHrRRSeV1yDHTsX4yYUAObwioAGYAnCAFskKxAcCCQyWX02Lx5TEF8AoOpQpAlI+UNXWIFvP0DEAGZksMRgvQyQAB1K7Fd-OjiE-KKQkojyuxjHagAjGDAoJALJHPi8oeLU6g62LN5e-sHEAFphvgo+IA
\begin{tikzcd} & & A \\
Z_1 \arrow[r, "\sigma"] \arrow[rru, "f_1", bend left] \arrow[rrd, "g_2", bend right] & Z_2 \arrow[ru, "f_2"] \arrow[rd, "g_2"] & \\ & & B
\end{tikzcd}
\end{document}
```

Flipping most arrows will give $\mathsf{C}^{A,B}$ the "coslice" version.
#### Proof
Identity: $\forall$ object $f:Z\to A$, $1_{f}\coloneqq1_{Z}$ is the identity.
Composition: $\forall$ morphism $\sigma:f_{1}\to f_{2},\tau: f_{2}\to f_{3}$, $\tau \sigma$ defined by the composition in $\mathsf{C}$ will make $f_{1}=f_{3}\tau \sigma$: