Book: [[MATH3030]]
# Definition (Presentations)
Let $G$ be a group and $A\subseteq G$ s.t. $G=\gen{A}$.
Since free groups are universal, $\exists!$ group homomorphism $\varphi:F(A)\to G$ s.t. the following diagram commutes:
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRADEAKAQQEoQAvqXSZc+QigBM5KrUYs2AcUHCQGbHgJEAjKW2z6zVohDdBsmFADm8IqABmAJwgBbJNJA4ISMnKNsAKxUHZzdEXy8kXT8FEwAdOJgADyw4HDgAQgT6RzQACyxgkCdXd2pIxGjDWJAE-Bw6cwEgA
\begin{tikzcd}
F(A) \arrow[rr, "\exists!\varphi"] & & G \\ & A \arrow[lu, "j"] \arrow[ru, "\iota"] & \end{tikzcd}
\end{document}
```
The presentation of $G$ is an explicit isomorphism $\overline{\varphi}:G\cong F(A)/R$ for some $R\unlhd F(A)$.
Elements of $A$ are called generators and elements of $R$ are called relations.

Note that a group can have many different presentations.
If we can find finite sets $A,\mathscr{R}$ s.t. $R=\gen{\mathscr{R}}$, we say that $G\cong F(A)/R$ is finitely presented and write $G=\gen{A|R}$.