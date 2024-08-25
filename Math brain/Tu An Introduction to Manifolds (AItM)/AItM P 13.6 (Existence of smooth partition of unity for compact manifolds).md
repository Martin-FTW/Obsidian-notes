Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 13.6 (Existence of smooth partition of unity for compact manifolds)
Let $M$ be a compact manifold and $\set{U_{\alpha}}_{\alpha\in \mathcal{A}}$ be an open cover of $M$.
Then $\exists$ a smooth partition of unity $\set{\rho_{\alpha}}_{\alpha\in \mathcal{A}}$ subordinate to $\set{U_{\alpha}}_{\alpha\in \mathcal{ A}}$.
#### Proof
For each $q\in M$, since $\set{U_{\alpha}}$ is a cover, we can find some $U_{\alpha}$ containing $q$.
Choose a smooth bump function $\psi_{q}$ at $q$ supported in $U_{\alpha}$.
Since $\psi_{q}(q)>0$ and $\psi_{q}$ is continuous, there is a nbhd $W_{q}$ of $q$ on which $\psi_{q}>0$.
Since $M$ is compact, the open cover $\set{W_{q}}_{q\in M}$ has a finite subcover $\set{W_{q_{j}}}_{j=1}^{m}$.
Now $\psi=\sum \psi_{q_{j}}$ is positive $\forall q\in M$ as $\set{W_{q_{j}}}$ is a cover
Define $\displaystyle \varphi_{j}=\frac{\psi_{q_{j}}}{\psi}$ for all $j\in\ii{1}{m}$
Clearly $\sum \varphi _{i}=1$. Moreover, since $\psi>0$, we have $\varphi _{i}(q)\neq 0\iff \psi_{q_{i}}(q)\neq 0$.
Thus $\supp\varphi _{i}=\supp\psi_{q_{i}}\subseteq U_{\alpha}$.
Now $\set{\varphi _{i}}$ is a partition of unity such that each $\varphi _{i}$ is supported in some $U_{\alpha}$
Denote that $\alpha$ by $\uptau(i)$. We now group $\set{\varphi _{i}}$ according to $\uptau(i)$:
For each $\alpha\in \mathcal{ A}$, define $\displaystyle \rho_{\alpha}=\sum_{i\in \uptau ^{-1}(\set{\alpha})}\varphi _{i}=\sum_{\uptau(i)=\alpha}\varphi _{i}$ using the empty sum convention.
Then $\displaystyle\sum_{\alpha\in \mathcal{A}}\rho_{\alpha}=\sum_{\alpha\in \mathcal{A}}\sum_{\uptau(i)=\alpha}\varphi _{i}=\sum_{i=1}^{m}\varphi _{i}=1$.
Since we also have $\displaystyle \supp \rho_{\alpha}\subseteq \bigcup_{\uptau(i)=\alpha}\supp \varphi_{i}\subseteq U_{\alpha}$