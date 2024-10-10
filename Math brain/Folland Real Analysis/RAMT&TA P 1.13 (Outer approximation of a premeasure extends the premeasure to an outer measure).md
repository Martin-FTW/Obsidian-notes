Book: [[Folland Real Analysis Modern Techniques and Their Application (RAMT&TA)]]
# Proposition 1.13 (Outer approximation of a premeasure extends the premeasure to an outer measure)
Let $X$ be a set and $\mathcal{A}$ be an algebra on $X$.
Let $\mu_{0}:\mathcal{A}\to \clcl{0}{\infty}$ be a premeasure on $\mathcal{A}$.
Let $\mu^*$ be the outer approximation of $\mu_{0}$, i.e. $\mu^*:\power(X)\to \clcl{0}{\infty}$ defined by $\displaystyle\mu^*(A)=\inf \set*{\sum_{j=1}^{\infty}\rho(E_{j})\given \exists(E_{j})\subseteq \mathcal{E}:A\subseteq\bigcup_{j=1}^{\infty}E_{j}}$.
Then $\mu^*$ extends $\mu_{0}$ and $\mathcal{A}\subseteq \mathcal{M}_{\mu^*}$, i.e.
1. $\mu^*\vert_{\mathcal{A}}=\mu_{0}$
2. Every set in $\mathcal{A}$ is $\mu^*$-measurable.
