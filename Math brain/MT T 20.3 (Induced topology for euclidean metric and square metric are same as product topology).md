Book: [[Munkres Topology (MT)]]
# Theorem 20.3 (Induced topology for euclidean metric and square metric are same as product topology)
Title, on $\mathbb{R}^{n}$
#### Proof
Let $x=(x_{1},\dots,x_{n}),y=(y_{1},\dots,y_{n})\in \mathbb{R}^{n}$.
Then $\rho(x,y)\leq d(x,y)\leq \sqrt{ n }\rho(x,y)$.
Now for each $x\in X$ and $\epsilon>0$, we have
- $B_{d}(x,\epsilon)\subset B_{\rho}(x,\epsilon)$
- $B_{\rho}\left( x, \frac{\epsilon}{\sqrt{ n }} \right)\subset B_{d}(x,\epsilon)$.

Hence by [[MT L 20.2 (Comparing metric topologies)]], we have both topologies are finer than each other.

Now let $B=\prod(a_k,b_{k})$ be a basis element for the product topology.
Let $x=(x_{1},\dots,x_{n})\in B$.
Then $\forall i\in\ii{1}{n}:\exists\epsilon_{i}>0:(x_{i}-\epsilon_{i},x_{i}+\epsilon_{i})\subset (a_{i},b_{i})$.
Take $\epsilon=\min \set{\epsilon_{i}}_{i=1}^{n}$. Then $x\in B_{\rho}(x,\epsilon)\subset B$.
Hence the $\rho$-topology is finer than the product topology on $\mathbb{R}^{n}$.
Now let $B_{\rho}(x,\epsilon)$ be a basis element for the $\rho$-topology.
But $B_{\rho}(x,\epsilon)=\prod(x_{i}-\epsilon,x_{i}+\epsilon)$ is a basis element for the product topology
Hence the product topology is finer than the $\rho$-topology.