Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 12.12 (Characterization of smooth sections)
Let $\pi:E\to M$ be a smooth vector bundle and $U\subseteq M$ be open.
Let $s_{1},\dots,s_{r}$ be a smooth frame for $E$ over $U$.
Let $s=\sum c^{j}s_{j}$ be a section of $E$ over $U$.
Then $s$ is smooth iff $c^{j}\in C^{\infty}(TU)$ for all $j\in\ii{1}{r}$
#### Proof
 $(\implies):$ Suppose $s$ is smooth. 
 Let $p\in U$ and choose a trivializing open set $V\subseteq U$ for $E$ containing $p$.
 Denote by $\phi:\pi ^{-1}(V)\to V\times \mathbb{R}^{r}$ its smooth trivialization.
 Let $t_{1},\dots,t_{r}$ be the smooth frame of $\phi$.
 Now write $s=\sum b^{i}t_{i}$ and $s_{j}=\sum a_{j}^{i}t_{i}$ for all $j$.
 Then we have $\sum b^{i}t_{i}=s=\sum c^{j}s_{j}=\sum c^{j}a^{i}_{j}t_{i}$.
 Thus $b^{i}=\sum c^{j}a_{j}^{i}$
 Now write $A=[a_{j}^{i}],b=[b^{i}], c=[c^{j}]$. Thus $b=Ac$.
 Since $A$ is a transition matrix between two bases, it is invertible.
Thus by Cramer's rule, $A^{-1}$ is a matrix of smooth functions on $V$ ([[AItM Eg 6.21 (General linear group as a Lie group)]]).
Hence $c=A^{-1}b$ is a matrix of smooth functions on $V$, in particular smooth at $p$.
Since $p$ is arbitrary, it follows that $c^{j}$ are all smooth on $U$
$(\impliedby):$ Suppose all $c^{j}$ are smooth.
Then $s$ is smooth by [[AItM P 12.9 (The vector space of all smooth sections of a smooth vector bundle is a module over the ring of smooth functions on the manifold)]]