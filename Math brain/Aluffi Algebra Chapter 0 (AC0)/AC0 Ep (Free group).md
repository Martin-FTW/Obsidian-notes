Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Exposition (Free group)
Let $A$ be a set.
Construct the category $\mathscr{F}^{A}$ by:
- $\obj \mathscr{F}^{A}$ consists of $(j,G)$ where $G$ is a group and $j:A\to G$ is a set-function.
- $\hom((j_{1},G_{1}),(j_{2},G_{2}))$ consists of commutative diagrams of the following shape where $\varphi:G_{1}\to G_{2}$ is a group homomorphism:
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\usepackage{amsfonts}
\newcommand\mfbox[1]{\fbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}\newcommand\mmbox[1]{\mbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBoBGAXVJADcBDAGwFcYkQBBEAX1PU1z5CKMsWp0mrdgHEA+uR58QGbHgJFypMTQYs2iEHIBMPcTCgBzeEVAAzAE4QAtkjIgcEJJol72AK3lFO0cXRDcPJCMdSX0QAJMaRnoAIxhGAAUBNWEQeywLAAscIJAHZy8aCMQonykDAB16hns0AqxTbiA
\begin{tikzcd}
G_1 \arrow[r, "\varphi"] & G_2 \\
A \arrow[u, "j_1"] \arrow[ru, "j_2"'] & \end{tikzcd}
\end{document}
```

Then the free group $F(A)$ the group component of an initial object in $\mathscr{F}^{A}$.

Note that this is a special case of a comma category, specified below:
Let $1$ be the one category, $\tilde{A}:1\to \mathsf{Set}$ be the selector functor $\tilde{A}(*)=A,\tilde{A}(\id_{*})=\id_{A}$.
Let $\mathscr{G}:\mathsf{Grp}\to \mathsf{Set}$ be the forgetful functor.
Then $\mathscr{F}^{A}=(A\downarrow\mathscr{G})\coloneqq(\tilde{A}\downarrow \mathscr{G})$, where the objects $(*,(G,\cdot),h:\tilde{A}(*)\to \mathscr{G}((G,\cdot)))=(*,(G,\cdot),h:A\to G)$ is identified with $(h, G)$