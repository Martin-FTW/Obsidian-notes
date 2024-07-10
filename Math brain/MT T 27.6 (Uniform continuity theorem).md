Book: [[Munkres Topology (MT)]]
# Theorem 27.6 (Uniform continuity theorem)
Let $f:(X,d_{X})\to (Y, d_{Y})$ be continuous.
Suppose $X$ is compact.
Then $f$ is uniformly continuous.
#### Proof
Let $\epsilon>0$.
Then $\set{B_{d_{Y}}(y,\epsilon/2)}_{y\in Y}$ is an open covering for $Y$.
Since $f$ is continuous, $\mathscr{A}\coloneqq \set{f^{-1}(B_{d_{Y}}(y,\epsilon/2))}_{y\in Y}$ is an open covering for $X$.
Choose $\delta>0$ a Lebesgue number for $\mathscr{A}$ by [[MT L 27.5 (Lebesgue number lemma)]].
Let $x_{1},x_{2}\in X$ s.t. $d_{X}(x_{1},x_{2})<\delta$.
Then $\diam\set{x_{1},x_{2}}<\delta$.
Hence $\exists A\in \mathscr{A}$ s.t. $\set{x_{1},x_{2}}\subset A$.
By definition of $\mathscr{A}$, $\exists y\in Y$ s.t. $A=f^{-1}(B_{d_{X}}(y,\epsilon/2))$.
Now $\set{f(x_{1}),f(x_{2})}=f(\set{x_{1},x_{2}})\subset f(f^{-1}(B_{d_{Y}}(y,\epsilon/2)))\subset B_{d_{Y}}(y,\epsilon/2)$.
It follows that $d_{Y}(f(x_{1}),f(x_{2}))\leq d_{Y}(f(x_{1}),y)+d_{Y}(y,f(x_{2}))<\epsilon$.
