Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Bundle map)
Let $\pi_{E}:E\to M,\pi_{F}:F\to N$ be two vector bundles.
Let $f:M\to N,\tilde{f}:E\to F$ be maps between manifolds
We call $(f,\tilde{f})$ a *bundle map* if 
1. $\pi_{F}\circ \tilde{f}=f\circ \pi_{E}$, i.e. the following diagram commutes:
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\usepackage{amsfonts}
\newcommand\mfbox[1]{\fbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}\newcommand\mmbox[1]{\mbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAFEQBfU9TXfIRQBGclVqMWbAGLdeIDNjwEiZYePrNWiEAFk5fJYKKj11TVJ0A5buJhQA5vCKgAZgCcIAWyRkQOCCQAJnNJbRAAHQi0LAB9TmoGOgAjGAYABX5lIRB3LAcACxwDEA9vX2oApFEJLTYovAZYYFcuErKfRBqqxABmULqdKJjY2R43T06Q-0C+gctSkESUtMyjFR08wuKuCi4gA
\begin{tikzcd}
E \arrow[d, "\pi_E"'] \arrow[r, "\tilde{f}"] & F \arrow[d, "\pi_F"] \\
M \arrow[r, "f"'] & N \end{tikzcd}
\end{document}
```
2. $\tilde{f}$ is linear on each fiber $E_{p}=\pi_{E} ^{-1}(p)$, i.e. $\forall p\in M:\tilde{f}|_{E_{p}}:E_{p}\to F_{f(p)}$ is a linear map

Vector bundles as objects and bundle maps as morphisms forms a category
Now note that any smooth map $f:N\to M$ induces a bundle map $(f,\tilde{f})$ where $\tilde{f}:TN\to TM$ is given by $\tilde{f}(p,v)=(f(p),f_{*}(v))\in \set{f(p)}\times T_{f(p)}M$.
This gives rise to a covariant functor $T$ from the cateogry of smooth manifolds $\mathbf{Man}^{\infty}$ to the category of smooth vector bundles, defined by $T(M)\coloneqq TM$ and $T(f)=(f,\tilde{f})$.