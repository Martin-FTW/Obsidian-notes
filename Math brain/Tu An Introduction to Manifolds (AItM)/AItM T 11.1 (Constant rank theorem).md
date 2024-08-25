Book: [[Tu An Introduction to Manifolds (AItM)]]
# Theorem 11.1 (Constant rank theorem)
Let $N,M$ be manifolds of dimensions $n,m$ respectively.
Let $p\in N$ and $f:N\to M$.
Suppose $f$ has constant rank $k$ in a neighbourhood of $p$ in $N$
Then $\exists$ charts $(U,\phi)$ centered at $p$ in $N$, $(V,\psi)$ centered at $f(p)$ in $M$ s.t.
- $\forall r=(r^{1},\dots,r^{n})\in \phi(U):(\psi \circ f\circ \phi ^{-1})(r)=(r^{1},\dots,r^{k},0,\dots,0)$

#### Proof
Choose a chart $(\bar{U},\bar{\phi})$ about $p$ in $N$ and $(\bar{V},\bar{\psi})$ about $f(p)$ in $M$.
Then $\bar{\psi}\circ f\circ \bar{\phi}^{-1}:\mathbb{R}^{n}\to \mathbb{R}^{m}$ has constant rank $k$ in a neighbourhood of $\bar{\phi}(p)$ since $\bar{\phi},\bar{\psi}$ are diffeomorphisms.
By the constant rank theorem for Euclidean spaces, $\exists$ neighbourhoods $U\subseteq \mathbb{R}^{n}$ of $\bar{\phi}(p)$ and $V\subseteq \mathbb{R}^{m}$ of $(\bar{\psi}\circ f)(P)$ and diffeomorphisms $G:U\to \mathbb{R}^{n},F:V\to \mathbb{R}^{m}$ s.t. $(F\circ \bar{\psi}\circ f\circ \bar{\phi}^{-1}\circ G^{-1})(r^{1},\dots,r^{n})=(r^{1},\dots,r^{k},0,\dots,0)$.
Now set $\phi=G\circ \bar{\phi}:\bar{\phi}^{-1}(U)\to \mathbb{R}^{n},\psi=F\circ \psi:\bar{\psi}^{-1}(V)\to \mathbb{R}^{m}$.
Thus $(\bar{\phi}^{-1}(U),\phi),(\bar{\psi}^{-1}(V),\psi)$ suffices