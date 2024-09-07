Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 16.2 (Tangent space to special linear group at identity)
Let $X\in T_{I}\SL(n,\mathbb{R})$.
Choose a curve $c$ in $\SL(n,\mathbb{R})$ s.t. $c(0)=I,c'(0)=X$.
Now by definition of $\SL(n,\mathbb{R})$, we have $\det c(t)=1$ for all $t$.
Differentiating both sides gives $0=\left.\frac{d}{dt}\right\vert_{0}(\det {}\circ c)=(\det{}\circ c)_{*}\left( \left.\frac{d}{dt}\right\vert_{0} \right)=\det_{*,I}\left( c_{*,0}\left( \left.\frac{d}{dt}\right\vert_{0} \right) \right)=\det_{*,I}(c'(0))=\tr X$.
Hence $T_{I}\SL(n,\mathbb{R})\subseteq V=\set{X\in \mathbb{R}^{n\times n}\given \tr X=0}$.
Since $\dim V=n^{2}-1=\dim T_{I}\SL(n,\mathbb{R})$, the spaces are equal.