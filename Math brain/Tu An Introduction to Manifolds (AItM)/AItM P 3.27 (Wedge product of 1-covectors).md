Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 3.27 (Wedge product of 1-covectors)
Let $F$ be a field and $V$ be a vector space over $F$.
Let $\alpha^{1},\dots,\alpha ^{k}\in V\dual$ and $v_{1},\dots,v_{k}\in V$.
Then $(\alpha^{1}\wedge\cdots\wedge \alpha ^{k})(v_{1},\dots,v_{k})=\det[\alpha ^{i}(v_{j})]$.
#### Proof
$(\alpha^{1}\wedge \cdots\wedge \alpha^{k})(v_{1},\dots,v_{k})$
$=A(\alpha^{1}\otimes \cdots\otimes \alpha^{k})(v_{1},\dots,v_{k})$
$\displaystyle =\sum_{\sigma\in S_{k}}(\sgn \sigma)\sigma(\alpha^{1}\otimes \cdots\otimes \alpha^{k})(v_{1},\dots,v_{k})$
$\displaystyle =\sum_{\sigma\in S_{k}}(\sgn \sigma)(\alpha^{1}\otimes \cdots\otimes \alpha^{k})(v_{\sigma(1)},\dots,v_{\sigma(k)})$
$\displaystyle =\sum_{\sigma\in S_{k}}(\sgn \sigma)\alpha^{1}(v_{\sigma(1)})\cdots\alpha^{k}(v_{\sigma(k)})$
$=\det[\alpha^{i}(v_{j})]$.