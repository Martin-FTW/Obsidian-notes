Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 16.7 (Left-invariant vector fields on general linear space)
Let $g\in\GL(n,\mathbb{R})\subseteq \mathbb{R}^{n\times n}$. Then $T_{g}\GL(n,\mathbb{R})\simeq \mathbb{R}^{n\times n}$.
Now if $(U,(x_{ij}))$ is a chart about $g$, we have the identification $\displaystyle \sum a_{ij}\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{g}\leftrightarrow[a_{ij}]$.
Now let $\displaystyle B=\sum b_{ij}\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{I}\in T_{I}\GL(n,\mathbb{R})$. Also write $B=[b_{ij}]$.
Denote by $\tilde{B}$ the left-invariant vector field on $\GL(n,\mathbb{R})$.
Then $\tilde{B}_{g}=(\ell_{g})\pushforward B\leftrightarrow gB$ by [[AItM Eg 8.19 (Differential of left multiplication in general linear group)]].
Now in terms of the basis $\set*{\displaystyle \left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{g}}$, we have $\displaystyle \tilde{B}_{g}=\sum_{i,j}(gB)_{ij}\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{g}=\sum_{i,j}\left( \sum_{k}g_{ik}b_{kj} \right)\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{g}$
