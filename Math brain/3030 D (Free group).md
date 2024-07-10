Book: [[MATH3030]]
# Definition (Free group)
Let $A$ be a set.
Consider the category $\mathscr{F}^{A}$ defined by
- $\obj(\mathscr{F}^{A})=\set{(j,G)\given G\in \obj\mathsf{Grp},j\in \hom_{\mathsf{Set}}(A,G)}$
- $\hom_{\mathscr{F}^{A}}((j_{1},G_{1}),(j_{2},G_{2}))=\set{\varphi\in \hom_{\mathsf{Grp}}(G_{1},G_{2})\given j_{2}=\varphi j_{1}}$, i.e. the commutative diagrams below s.t. $\varphi$ is a group homomorphism:
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAHEB9ARhAF9S6TLnyEUAJnJVajFmy7j+gkBmx4CRbqW7T6zVohABBftJhQA5vCKgAZgCcIAWySSQOCEjIz9bAFY8SnaOLojeHkhaPnKGADqx9PZoABZYQSAOzq7UEYhRejEgAYp8FHxAA
\begin{tikzcd}
G_1 \arrow[rr, "\varphi"] & & G_2 \\ & A \arrow[lu, "j_1"] \arrow[ru, "j_2"] & \end{tikzcd}
\end{document}
```


The (group component) of an initial object in $\mathscr{F}^{A}$ is called the free group $F(A)$ on $A$.