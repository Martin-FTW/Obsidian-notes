Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Section, smooth section)
Let $\pi:E\to M$ be a vector bundle.
Let $s:M\to E$ be a map.
We call $s$ a *section of $E$* if $\pi \circ s=\mathbb{1}_{M}$.
That is, it maps each point $p\in M$ into the fiber $E_{p}$ above $p$.
We call a section $s:M\to E$ *smooth* if it is a smooth map between the manifolds $M$ and $E$.
The set of all smooth sections of $E$ is denoted by $\Gamma(E)$.
Note that $\Gamma(E)$ is a vector space over $\mathbb{R}$ with addition $s+t:M\to E$ defined pointwise $(s+t)(p)=s(p)+t(p)\in E_{p}$, inheriting the linear structure in $E_{p}$.

If $U\subseteq M$ is open, a map $s:U\to E$ is called a section of $E$ over $U$ if $\pi|_{U}\circ s=\mathbb{1}_{U}$.
The set of all smooth sections of $E$ over $U$ is denoted by $\Gamma(U,E)$, and is similarly a vector space over $\mathbb{R}$.
Note that $\Gamma(M,E)=\Gamma(E)$, thus in contrast to proper subsets $U$, we call a section over the entire manifold $M$ a global section