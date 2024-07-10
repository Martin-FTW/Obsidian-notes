Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Definition (Shape operator)
Let $S$ be a regular surface with orientation $N$.
Let $p\in S$.
Define $S_{p}:T_{p}S\to T_{N(p)}\mathbb{S}^{2}$ by $S_{p}=-dN_{p}$, i.e.
- $\forall v\in T_{p}S:S_{p}(v)\coloneqq-(N\circ \alpha)'(t)$, where $\alpha:(-\varepsilon,\varepsilon)\to S$ is a differentiable curve on $S$ with $\alpha(0)=p,\alpha'(0)=v$.

We call $S_{p}$ the shape operator w.r.t. $N$ at $p$.
Note that $T_{N(p)}\mathbb{S}^{2}\cong T_{p}S$, thus we sometimes write $S_{p}:T_{p}S\to T_{p}S$ to mean $\varphi \circ S_{p}$, where $\varphi$ is an isomorphism between $T_{N(p)}\mathbb{S}^{2}$ and $T_{p}S$.