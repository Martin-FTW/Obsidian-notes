d+# Smooth manifold coordinates
Let $N,M$ be a manifolds
Let $p\in N$, $F:N\to M$ and $q=F(p)\in M$.
Let $(U,\phi)=(U,x^{1},\dots,x^{n}),(\tilde{U},\tilde{\phi})=(U,\tilde{x}^{1},\dots,\tilde{x}^{n})$ be charts about $p$.
Let $(V,\psi)=(V,y^{1},\dots,y^{m})$ be a chart about $q$.

1. Let $v\in T_{p}N,v^{i}=dx_{p}^{i}(v),\tilde{v}^{i}=d\tilde{x}_{p}^{i}(v)$.  
	- $\displaystyle v=v^{i}\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}=\tilde{v}^{i}\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}$
	- $\displaystyle \tilde{v}^{j}=v^{i}\frac{ \partial \tilde{x}^{j} }{ \partial x^{i} }(p)$
	- $\displaystyle \frac{ \partial }{ \partial \tilde{x}^{j} }=dx^{i}\left( \frac{ \partial }{ \partial \tilde{x}^{j} } \right)\frac{ \partial }{ \partial x^{i} }=\frac{ \partial x^{i} }{ \partial \tilde{x}^{j} }\frac{ \partial }{ \partial x^{i} }$.
2. Let $\displaystyle \alpha\in T_{p}^*N,\alpha_{i}=\frac{ \partial f }{ \partial x^{i} }(p),\tilde{\alpha}_{i}=\frac{ \partial f }{ \partial \tilde{x}^{i} }(p)$, by $\exists f\in C^{\infty}(U):\alpha=df_{p}$
	- $\alpha=\alpha_{i}dx_{p}^{i}=\tilde{\alpha}_{i}d\tilde{x}_{p}^{i}$.
	- $\displaystyle \tilde{\alpha}_{j}=\alpha_{j}\frac{ \partial x^{i} }{ \partial \tilde{x}^{j} }(p)$
	- $\displaystyle d\tilde{x}_{p}^{j}=\frac{ \partial \tilde{x}^{j} }{ \partial x^{i} }(p)dx_{p}^{i}$

3. Let $w=dF_{p}(v)\in T_{q}M,w^{i}=dy_{q}^{i}(w),F^{i}=y^{i}\circ F$ 
	- $\displaystyle w=w^{i}\left.\frac{ \partial }{ \partial y^{i} }\right\vert_{q}$ (by 1)
	- $\displaystyle w^{j}=v^{i}\frac{ \partial F^{j} }{ \partial x^{i} }(p)$
	- $\displaystyle dF_{p}\left( \left.\left.\frac{ \partial }{ \partial x^{j} }\right\vert_{p} \right)=\frac{ \partial F^{i}}{ \partial x^{j} }(p)\frac{ \partial }{ \partial y^{i} }\right\vert_{F(p)}$

4. Let $g_{p}$ be a metric tensor at $p$, $ds^{2}$ be its corresponding quadratic form, and $\displaystyle g_{ij}=g_{p}\left( \left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p},\left.\frac{ \partial }{ \partial x^{j} }\right\vert_{p} \right),\tilde{g}_{k\ell}=g_{p}\left( \left.\frac{ \partial }{ \partial \tilde{x}^{i} }\right\vert_{p},\left.\frac{ \partial }{ \partial \tilde{x}^{j} }\right\vert_{p} \right)$.
- $ds^{2}=g_{ij}dx^{i}dx^{j}$, i.e. $ds^{2}(v)=g_{ij}dx^{i}(v)dx^{j}(v)$l
- $\displaystyle \tilde{g}_{k\ell}=g_{ij}\frac{ \partial x^{i} }{ \partial \tilde{x}^{k} }(p)\frac{ \partial x^{j} }{ \partial \tilde{x}^{\ell} }(p)$
5.  Let $T$ be a tensor at $p$ 
- $\begin{align}\displaystyle \tilde{T}^{i_{1}'\dots i_{r}'}_{j_{1}'\dots j_{s}'}&=\sum_{i_{1},\dots,i_{r},j_{1},\dots,j_{s}=1}^{n} T^{i_{1}\dots i_{r}}_{j_{1}\dots j_{s}}\prod_{k=1}^{r} \frac{ \partial \tilde{x}^{i_{k}'} }{ \partial x^{i_{k}} }(p)\prod_{k=1}^{s} \frac{ \partial x^{j_{k}} }{ \partial \tilde{x}^{j_{k}'} }(p)\\&=T^{i_{1}\dots i_{r}}_{j_{1}\dots j_{s}}\frac{ \partial \tilde{x}^{i_{1}'} }{ \partial x^{i_{1}} }\cdots\frac{ \partial \tilde{x}^{i_{r}'} }{ \partial x^{i_{r}} }\frac{ \partial x^{j_{1}} }{ \partial \tilde{x}^{j_{1}'} }\cdots \frac{ \partial x^{j_{s}} }{ \partial \tilde{x}^{j_{s}'} }\end{align}$