Book: [[Munkres Topology (MT)]]
# Theorem 22.2 (Universal property of quotient map)
Let $p:X\to Y$ be a quotient map.
Let $Z$ be a topological space.
Let $g:X\to Z$ be a function s.t. $g|_{p^{-1}(\set{y})}$ is constant $\forall y\in Y$.
Then $\exists!f:Y\to Z$ s.t. $g=f\circ p$.
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAA0QBfU9TXfIRRkAjFVqMWbAJrdeIDNjwEiI0mOr1mrRCABa3cTCgBzeEVAAzAE4QAtkjIgcEJGona2aENQZ0ARjAMAAr8ykIg1lgmABY4cla2DojuLkgATJqSOiAAOrkwAB5YcDhwAIQABJY+IH6BIWGCbFGx8TyJ9o7UaYiZHlK6+ZYQ1owMlSaGXEA
\begin{tikzcd}
X \arrow[d, "p"'] \arrow[rd, "\forall g"] & \\
Y \arrow[r, "\exists! f"'] & Z
\end{tikzcd}
\end{document}
```
In this case, we have
- $f$ is continuous iff $g$ is continuous
- $f$ is a quotient map iff $g$ is a quotient map