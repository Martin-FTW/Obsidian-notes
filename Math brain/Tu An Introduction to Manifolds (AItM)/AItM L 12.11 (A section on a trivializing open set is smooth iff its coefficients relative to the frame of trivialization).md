Book: [[Tu An Introduction to Manifolds (AItM)]]
# Lemma 12.11 (A section on a trivializing open set is smooth iff its coefficients relative to the frame of trivialization)
Let $\pi:E \to M$ be a smooth vector bundle.
Let $\phi:E|_{U}\to U\times \mathbb{R}^{r}$ be a trivialization of $E$.
Let $t_{1},\dots,t_{r}$ be the smooth frame over $U$ over the trivialization $\phi$.
Let $s=\sum b^{i}t_{i}$ be a section of $E$ over $U$.
Then $s$ is smooth iff $b^{i}$ are smooth for all $i\in\ii{1}{r}$.
#### Proof
$(\implies):$ Suppose $s$ is smooth.
Now $(\phi \circ s)(p)=\phi\left( \sum b^{i}(p)t_{i}(p) \right)=\sum b^{i}(p)\phi(t_{i}(p))=\sum b^{i}(p)(p,e_{i})=\left( p,\sum b^{i}(p)e_{i} \right)$.
Hence $b^{i}$ are the fiber coordinates of the smooth trivialization $\phi$
Since $\phi$ is a diffeomorphism, $\phi \circ s$ is smooth, thus $b^{i}$ are all smooth.
$(\impliedby):$
Follows from [[AItM P 12.9 (The vector space of all smooth sections of a smooth vector bundle is a module over the ring of smooth functions on the manifold)]]