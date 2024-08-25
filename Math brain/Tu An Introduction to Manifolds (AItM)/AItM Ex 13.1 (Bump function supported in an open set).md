Book: [[Tu An Introduction to Manifolds (AItM)]]
# Exercise 13.1 (Bump function supported in an open set)
Let $M$ be a manifold, $q\in M$, and $U$ be a nbhd of $q$.
Construct a smooth bump function at $q$ supported in $U$.
#### Proof
Let $(V,\phi)$ be a chart centered at $q$ with $V\subseteq U$.
Let $b=\frac{1}{2}d(\vec{0},\partial (\phi(V)))=\frac{1}{2}\inf \set{d(\vec{0},p)\given p\in \partial \phi(V)}$
The the bump function $\sigma(x)$ in [[AItM R (Construction of bump functions)]] is supported in $\overline{B}(\vec{0},b)\subseteq \phi(V)$.
Hence $\sigma \circ \phi$ is a bump function at $q$ in $M$ supported in $\phi ^{-1}(\phi(V))=V\subseteq U$.