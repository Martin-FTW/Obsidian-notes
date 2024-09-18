Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Proposition II.6.6 (Universal property of kernel of a group homomorphism)
Let $\varphi:G\to G'$ be a group homomorphism.
Denote by $0$ the trivial homomorphism.
Then the inclusion $i:\ker \varphi \hookrightarrow G$ is final in the category of group homomorphisms $\alpha:K\to G$ s.t. $\varphi \circ \alpha=0$.
That is, $\forall$ group homo $\alpha:K\to G$ s.t. $\varphi \circ \alpha=0$, $\exists!\bar{\alpha}:K\to \ker \varphi$ s.t. $\alpha=i\circ \bar{\alpha}$, i.e. $\alpha$ factors uniquely through $\ker \varphi$.

The category $\mathsf{C}$ above is defined by
- $\obj \mathsf{C}$ consists of $(\alpha,K)$ where $K$ is a group and $\alpha:G\to K$ is a group homomorphism (or set-function, see [[AC0 R II.6.7 (Stronger universal property of kernels with set-functions)]]) s.t. $\varphi \circ \alpha=0$
- $\hom_{\mathsf{C}}((\alpha,K),(\alpha',K'))$ consists of $\sigma:K\to K'$ s.t. $\alpha=\alpha'\circ \sigma$, i.e. the following diagram commutes:
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\usepackage{amsfonts}
\newcommand\mfbox[1]{\fbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}\newcommand\mmbox[1]{\mbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZARgBpiBdUkANwEMAbAVxiRAHEQBfU9TXfIRQAmclVqMWbdgHJuvEBmx4CRAAyk14+s1aIQAaXl9lg9aWHbJew3K7iYUAObwioAGYAnCAFskokBwIJA0JXTYAHQjGNAALOhBqBjoAIxgGAAV+FSEQTywnWJxjEC9fEOogpDIwqX0o+k84rESQZLTM7LN9fMLing9vP0QAqsQatLAoJABmUJ06kDVW9vSs01UegqKSsuGZyuDEeetI6IY4ujsFPdnD6upJ6cQAWjnqBZtlgdKh-3vEAdajYotgnD4EvYuEA
\begin{tikzcd}
K \arrow[rd, "\alpha"'] \arrow[rrd, "0"', bend left] \arrow[dd, "\sigma"] & & \\ & G \arrow[r, "\varphi"'] & G' \\
K' \arrow[ru, "\alpha'"] \arrow[rru, "0", bend right] & & \end{tikzcd}
\end{document}
```

