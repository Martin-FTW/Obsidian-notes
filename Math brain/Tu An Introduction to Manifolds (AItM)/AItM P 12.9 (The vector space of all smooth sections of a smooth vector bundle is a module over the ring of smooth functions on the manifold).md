Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 12.9 (The vector space of all smooth sections of a smooth vector bundle is a module over the ring of smooth functions on the manifold)
Let $M$ be a manifold and $\pi: E\to M$ be a smooth vector bundle on $M$.
Define addition and scalar multiplication on $\Gamma(M)$ by:
1. $\forall s,t\in \Gamma(M)$, define $s+t:M\to E$ by $(s+t)(p)=s(p)+t(p)\in E_{p}$
2. $\forall s\in \Gamma(M),f\in C^{\infty}(M)$, define $fs:M\to E$ by $(fs)(p)=f(p)s(p)\in E_{p}$.

Then $s+t$ and $fs$ are smooth sections of $E$.
This makes $\Gamma(M)$ into a module over $C^{\infty}(M)$
Similarly, the vector space $\Gamma(U,E)$ of smooth sections of $E$ over $U$ is a module over $C^{\infty}(U)$.
#### Proof
Note that $s+t$ and $fs$ are obviously sections.
Let $p\in M$ and $V$ be a trivializing open set for $E$ containing $p$ with smooth trivialization $\phi:\pi ^{-1}(V)\to V\times \mathbb{R}^{r}$.
Let $(\phi \circ s)(q)=(q,a^{1}(q),\dots,a^{r}(q)),(\phi \circ t)(q)=(q,b^{1}(q),\dots,b^{r}(q))$ by definition that $\pi \circ s=\mathbb{1}_{M}$.
Since $s,t$ are smooth, we have $a^{i},b^{i}$ are all smooth on $V$ by [[AItM P 6.16 (Smoothness of a map in terms of components)]].
Now since $\phi$ is a linear isomorphism on each fiber, in particular linear, for any $q\in V$ we have $(\phi \circ(s+t))(q)=\phi(s(q)+t(q))=\phi(s(q)+\phi(t(q)))=(q,a^{1}(q)+b^{1}(q),\dots,a^{r}(q)+b^{r}(q))$
Since $\phi$ is smooth, we have $s+t=\phi ^{-1}\circ(\mathbb{1}_{M},a^{1}+b^{1},\dots,a^{r}+b^{r})$ is a composition of smooth maps, thus is smooth on $V$, in particular smooth at $p$
Since $p$ is arbitrary $s+t$ is smooth on $M$.
Similarly, for any $q\in V$ we have $(\phi \circ(fs))(q)=\phi(f(q)s(q))=f(q)(\phi \circ s)(q)$
Since $f$ is smooth and $\phi \circ s$ is smooth we have $\phi \circ(fs)$ is smooth, thus $fs$ is smooth on $V$.
