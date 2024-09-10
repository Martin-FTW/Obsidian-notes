# Smooth manifold coordinates
Let $N,M$ be a manifolds
Let $p\in N$, $F:N\to M$ and $q=F(p)\in M$.
Let $(U,\phi)=(U,x^{1},\dots,x^{n}),(\tilde{U},\tilde{\phi})=(U,\tilde{x}^{1},\dots,\tilde{x}^{n})$ be charts about $p$.
Let $(V,\psi)=(V,y^{1},\dots,y^{m})$ be a chart about $q$.

1. Let $v\in T_{p}N,v^{i}=dx^{i}(v),\tilde{v}^{i}=d\tilde{x}^{i}(v)$.  Then $\displaystyle v=v^{i}\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}=\tilde{v}^{i}\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}$
- $\displaystyle \tilde{v}^{j}=v^{i}\left.\frac{ \partial \tilde{x}^{j} }{ \partial x^{i} }\right\vert_{p}$
- $\displaystyle \frac{ \partial }{ \partial \tilde{x}^{j} }=dx^{i}\left( \frac{ \partial }{ \partial \tilde{x}^{j} } \right)\frac{ \partial }{ \partial x^{i} }=\frac{ \partial x^{i} }{ \partial \tilde{x}^{j} }\frac{ \partial }{ \partial x^{i} }$.
2. Let $\omega\in T_{p}^*N,\omega_{i}=?,\tilde{\omega}_{i}=?$. Then $\omega=\omega_{i}dx_{p}^{i}=\tilde{\omega}_{i}d\tilde{x}_{p}^{i}$.
- $\displaystyle \tilde{\omega}_{j}=\omega_{j}\left.\frac{ \partial x^{i} }{ \partial \tilde{x}^{j} }\right\vert_{p}$
- $\displaystyle d\tilde{x}^{j}=\frac{ \partial \tilde{x}^{j} }{ \partial x^{i} }dx^{i}$

3. Let $w=dF_{p}(v)\in T_{q}M,w^{i}=dy^{i}(w)$ Then $\displaystyle w=w^{i}\left.\frac{ \partial }{ \partial y^{i} }\right\vert_{q}$ by 1.
- $\displaystyle w^{j}=v^{i}\left.\frac{ \partial y^{j} }{ \partial x^{i} }\right\vert_{p}$
