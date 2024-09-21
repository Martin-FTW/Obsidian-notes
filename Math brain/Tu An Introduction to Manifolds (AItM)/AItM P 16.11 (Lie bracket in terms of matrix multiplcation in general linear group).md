Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 16.11 (Lie bracket in terms of matrix multiplcation in general linear group)
Let $A,B\in T_{I}\GL(n,\mathbb{R})$.
Write $\displaystyle A=\sum a_{ij}\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{I},B=\sum b_{ij}\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{I}$.
Now if $\displaystyle \lie{A}{B}=\lie{\tilde{A}}{\tilde{B}}_{I}=\sum c_{ij}\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{I}$, then we have $c_{ij}=\sum_{k}a_{ik}b_{kj}-b_{ik}a_{kj}$.
That is, by identifying $\displaystyle \sum c_{ij}\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{I}\leftrightarrow[c_{ij}]$, we have $\lie{A}{B}=AB-BA$ in matrix multiplication.
#### Proof
Since $\displaystyle \lie{A}{B}=\lie{\tilde{A}}{\tilde{B}}_{I}=\sum c_{ij}\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{I}$, we have $\displaystyle c_{ij}=\sum c_{ij}\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{I}x_{ij}=\lie{\tilde{A}}{\tilde{B}}_{I}x_{ij}=\tilde{A}_{I}\tilde{B}x_{ij}-\tilde{B}_{I}\tilde{A}x_{ij}=A\tilde{B}x_{ij}-B\tilde{A}x_{ij}$.
By [[AItM Eg 16.7 (Left-invariant vector fields on general linear space)]], for any $g \in\GL(n,\mathbb{R})$ we have $\displaystyle \tilde{B}_{g}x_{ij}=\sum_{i,j}(gB)_{ij}\left.\frac{ \partial }{ \partial x_{ij} }\right\vert_{g}x_{ij}=(gB)_{ij}=\sum_{k} g_{ik}b_{kj}=\sum_{k}b_{kj}x_{ik}(g)$.
It follows that $\displaystyle \tilde{B}x_{ij}=\sum_{k}b_{kj}x_{ik}$.
Hence $\displaystyle A\tilde{B}x_{ij}=\sum_{p,q}a_{pq}\left.\frac{ \partial }{ \partial x_{pq} }\right\vert_{I}\left( \sum_{k} b_{kj}x_{ik} \right)=\sum_{p,q,k}a_{pq}b_{kj}\delta_{pi}\delta_{qk}=\sum_{k}a_{ik}b_{kj}=(AB)_{ij}$.
Similarly, we have $B\tilde{A}x_{ij}=(BA)_{ij}$.
It follows that $c_{ij}=(AB-BA)_{ij}$.