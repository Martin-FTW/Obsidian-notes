Book: [[Munkres Topology (MT)]]
# Theorem 20.4 (Uniform topology is finer than product but coarser than box)
Let $J$ be an index set.
The uniform topology on $\mathbb{R}^{J}$ is finer than the product topology and coarser than the box topology.
All equalities hold iff $J$ is finite.
#### Proof
Let $x=(x_{\alpha})_{\alpha\in J}\in \mathbb{R}^{J}$ and $\prod U_{\alpha}$ be a basis element containing $x$ in the product topology.
Let $\alpha_{1},\dots,\alpha_{n}$ be the finite indices where $U_{\alpha}\neq \mathbb{R}$.
Then $\forall i\in\ii{1}{n}:\exists\epsilon_{i}>0:(x_{\alpha_{i}}-\epsilon_{i},x_{\alpha_{i}}+\epsilon_{i})\subset U_{\alpha_{i}}$ since $U_{\alpha}$ are open in $\mathbb{R}$.
Let $\epsilon=\min \set{\epsilon_{i}}_{i=1}^{n}$. Then for any $\alpha\in J$, 
- if $\alpha\notin \set{\alpha_{i}}$ then $(x_{\alpha}-\epsilon,x_{\alpha}+\epsilon)\subset \mathbb{R}=U_{\alpha}$
- if $\alpha\in \set{\alpha_{i}}$ then $(x_{\alpha_{i}}-\epsilon,x_{\alpha_{i}}+\epsilon)\subset(x_{\alpha_{i}}-\epsilon_{i},x_{\alpha_{i}}+\epsilon_{i})\subset U_{\alpha_{i}}$

Hence $x\in B_{\bar{\rho}}(x,\epsilon)=\prod (x_{\alpha}-\epsilon,x_{\alpha}+\epsilon) \subset \prod U_{\alpha_{i}}$.
It follows that the uniform topology is finer than the product topology

Now let $B_{\bar{\rho}}(x,\epsilon)$ a basis element for the $\bar{\rho}$ topology.
Then $U=\prod\left( x_{\alpha}- \frac{1}{2}\epsilon,x_{\alpha}+ \frac{1}{2}\epsilon \right)$ is a neighbourhood of $x$ that is contained in  $B_{\bar{\rho}}(x,\epsilon)$ in the box topology.
Hence $B_{\bar{\rho}}(x,\epsilon)$ is open in the box topology.