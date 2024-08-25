Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition 13.4 (Smooth partition of unity)
Let $M$ be a manifold.
Let $\set{\rho_{\alpha}}_{\alpha \in \mathcal{A}}\subseteq C^{\infty}(M)$ be a collection of nonnegative smooth functions, that is $\rho_{\alpha}\geq 0$ for all $\alpha\in \mathcal{A}$
We call $\set{\rho_{\alpha}}$ a partition of unity on $M$ if 
1. $\set{\supp \rho_{\alpha}}_{\alpha\in \mathcal{A}}$ is locally finite
2. $\sum \rho_{\alpha}=1$

Further suppose $\set{U_{\alpha}}_{\alpha\in \mathcal{ A}}$ is an open cover of $M$.
We say that the partition of unity $\set{\rho_{\alpha}}_{\alpha\in \mathcal{A}}$ is subordinate to $\set{U_{\alpha}}$ if each $\rho_{\alpha}$ is supported in $U_{\alpha}$, i.e. $\forall \alpha\in \mathcal{A}:\supp\rho_{\alpha}\subseteq U_{\alpha}$