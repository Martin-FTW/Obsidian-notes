Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Fiber, fiber-preserving maps, local trivialization, vector bundle)
Let $E,M$ be topological spaces, $p\in M$ and $\pi:E\to M$.
We call $E_{p}\coloneqq\pi ^{-1}(p)$ the fiber at $p$.
If $\pi':E'\to M$ is another map, we call $\phi:E\to E'$ fiber-preserving if $\phi(\pi ^{-1}(p))\subseteq \pi'^{-1}(p)$

Now suppose $E,M$ are manifolds and $\pi:E\to M$ is surjective and smooth.
We call $\pi$ locally trivial of rank $r$ if:
1. $\forall p\in M:$ the fiber $\pi ^{-1} (p)$ is a vector space of dimension $r$
2. $\forall p\in M:\exists$ nbhd $U$ of $p$ and a fiber-preserving diffeomorphism $\phi:\pi ^{-1}(U)\to U\times \mathbb{R}^{r}$ s.t.
	- $\forall q\in U:\phi|_{\pi ^{-1}(q)}:\pi ^{-1}(q)\to \set{q}\times \mathbb{R}^{r}$ is a vector space isomorphism.

In this case, we call
1. $U$ a trivializing open set for $E$
2. $\phi$ a trivialization of $E$ over $U$

If $\set{U}$ is an open cover of $M$, we call it a trivializing open cover of $M$ for $E$ and $\set{(U,\phi)}$ a local trivialization for $E$.

Finally, we call $(E,M,\pi)$ a smooth vector bundle of rank $r$ if $E,M$ are manifolds and $\pi:E\to M$ is a surjective smooth map that is locally trivial of rank $r$.
We say (by abuse of language) that $E$ is a vector bundle over $M$.