Book: [[Munkres Topology (MT)]]
# Definition (Partition of unity)
Let $X$ be a topological space.
Let $\set{U_{\alpha}}_{\alpha\in J}$ be an indexed open covering of $X$.
Let $\phi_{\alpha}:X\to \clcl{0}{1}$ be an indexed family of continuos functions.
Denote $\supp \phi_{\alpha}=\cl_{X}(\phi ^{-1}(\opcl{0}{1}))=\cl_{X}(\set{x\in X\given\phi_{\alpha}(x)\neq 0})$.
We call $\set{\phi_{\alpha}}$ a partition of unity dominated by $\set{U_{\alpha}}$ if
1. $\forall \alpha\in J:\supp \phi_{\alpha}\subseteq U_{\alpha}$
2. $\set{\supp \phi_{\alpha}}_{\alpha\in J}$ is locally finite
3. $\sum \phi_{\alpha}\equiv 1$, i.e. $\forall x\in X:\sum_{\alpha} \phi_{\alpha}(x)=0$.

