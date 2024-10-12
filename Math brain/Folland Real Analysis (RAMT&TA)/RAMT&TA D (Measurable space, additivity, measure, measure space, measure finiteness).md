Book: [[Folland Real Analysis (RAMT&TA)]]
# Definition (Measurable space, additivity, measure, measure space, measure finiteness)
Let $X$ be a set and $\mathcal{M}\subseteq \power(X)$ be a $\sigma$-algebra.
We call $(X,\mathcal{M})$ a measurable space and elements in $\mathcal{M}$ are called measurable sets.
Let $\mu:\mathcal{M}\to \clcl{0}{\infty}$ be a function.
We call $\mu$:
- finitely additive if $\forall$ disjoint $E_{1},\dots,E_{n}\in \mathcal{M}$ s.t. $\displaystyle\mu\left(\bigcup_{j=1}^{n} E_{j}\right)=\sum_{j=1}^{n} \mu(E_{j})$
- countably additive if $\forall$ disjoint $\set{E_{j}}_{j=1}^{\infty}\subseteq \mathcal{M}$ s.t. $\displaystyle\mu\left(\bigcup_{j=1}^{\infty} E_{j}\right)=\sum_{j=1}^{\infty} \mu(E_{j})$\
- a measure if $\mu$ is countably additive and $\mu(\emptyset)=0$.

Suppose $\mu$ is a measure.
Then we call $(X,\mathcal{M},\mu)$ a measure space.
We call $\mu$ finite if $\mu(X)<\infty$.
We call $E\in \mathcal{M}$ $\sigma$-finite for $\mu$ if $E$ is of $\sigma$-finite measure, i.e. $\displaystyle \exists \set{E_{j}}_{j=1}^{\infty}\subseteq \mathcal{M}:E=\bigcup_{j=1}^{\infty}E_{j}$ and $\forall j\in \mathbb{Z}_{>0}:\mu(E_{j})<\infty$
We call $\mu$ $\sigma$-finite if $X$ is $\sigma$-finite for $\mu$.
We call $\mu$ semifinite if $\forall E\in \mathcal{M}:[\mu(E)=\infty]\to [\exists F\in \mathcal{M}:F\subseteq E,0<\mu(F)<\infty]$.
Note that finite $\implies$ $\sigma$-finite $\implies$ semifinite.