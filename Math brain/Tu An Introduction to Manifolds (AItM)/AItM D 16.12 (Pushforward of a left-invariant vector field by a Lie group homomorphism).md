Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition 16.12 (Pushforward of a left-invariant vector field by a Lie group homomorphism)
Let $F:H\to G$ be a Lie group homomorphism.
Define $F\pushforward:L(H)\to L(G)$ by $F\pushforward(\tilde{A})=(F\pushforward[,e]A)\tilde{\ }$ for all $A\in T_{e}H$.
We call $F\pushforward(\tilde{A})$ the pushforward of $\tilde{A}$ by $F$.
This pushforward is induced by the natural pushforward of the differential of $F$ in $T_{e}H$ and the isomorphism $\varphi:T_{e}G\iso L(G)$ in [[AItM D (Left-invariant vector field)]], by mapping according to the diagram
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\usepackage{amsfonts}
\newcommand\mfbox[1]{\fbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}\newcommand\mmbox[1]{\mbox{\begin{tabular}{@{}c@{}}#1\end{tabular}}}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBoBGAXVJADcBDAGwFcYkQAZACgAkBKEAF9S6TLnyEUZYtTpNW7ACoB9GAAIeQkSAzY8BIuVIyaDFm0QgV6gOJbReiYYqyzCy9xsDBsmFADm8ESgAGYAThAAtkhkIDgQSEZy5uwAOqkMYWgAFljKPAB6wAC05IL2IOFRiTTxSABMpvIWIABiysAAVKQw5cKhEdGIjXEJiADMTSmW6Zk5eXb9lYMxtWOTIIxYYC1Q9HDZfiBT7m3KnUKUgkA
\begin{tikzcd}
T_e H \arrow[r, "F_{*,e}"] & T_e G \arrow[d, "\varphi_G"] \\
L(H) \arrow[u, "\varphi_H^{-1}"] \arrow[r, "F_*", dashed] & L(G) \end{tikzcd}
\end{document}
```
