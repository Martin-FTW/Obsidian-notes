Book: [[Folland Real Analysis (RAMT&TA)]]
# Theorem 1.8 (Monotonicity, subadditivity, continuity from above and below)
Let $(X,\mathcal{M},\mu)$ be a measure space.
Then
1. $\mu$ is monotone, i.e. $\forall E,F\in \mathcal{M}:[E\subseteq F]\implies \mu(E)\leq \mu(F)$.
2. $\mu$ is subadditive, i.e. $\displaystyle \forall \set{E_{j}}_{j=1}^{\infty}\subseteq \mathcal{M}:\mu(\bigcup_{j=1}^{\infty}E_{j})\leq \sum_{j=1}^{\infty}\mu(E_{j})$.
3. $\mu$ is continuous from below, i.e. $\forall \set{E_{j}}_{j=1}^{\infty}\subseteq \mathcal{M}$, if $\forall i\in \mathbb{Z}_{>0}:E_{i}\subseteq E_{i+1}$ then $\displaystyle \mu (\lim(E_{j}))=\mu \left( \bigcup_{j=1}^{\infty}E_{j} \right)=\lim(\mu(E_{j}))$
4. $\mu$ is continuous from above, i.e. $\forall \set{E_{j}}_{j=1}^{\infty}\subseteq \mathcal{M}$, if $\mu(E_{1})<\infty$ and $\forall i:E_{i}\supseteq E_{i+1}$ then $\displaystyle \mu(\lim(E_{j}))=\mu \left( \bigcup_{j=1}^{\infty}E_{j} \right)=\lim(\mu(E_{j}))$