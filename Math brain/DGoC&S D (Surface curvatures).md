Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Definition (Surface curvatures)
Let $S$ be an oriented surface and $N:S\to \mathbb{S}^{2}$ be the Gauss map.
Let $p\in S,v\in T_{p}S$, and $S_{p}:T_{p}S\to T_{p}S$ be the shape operator of $S$ at $p$.
We call 
- $H$ the mean curvature of $S$ at $p$ (dependent on orientation $N$)
- $K$ the Gaussian curvature of $S$ at $p$ (independent of orientation $N$)
- $k_{v}$ the normal curvature of $S$ along $v$, or $k_{n}$ the normal curvature of $C$ at $p$
- $k_{1},k_{2}$ the principal curvatures of $S$ at $p$, and $e_{1},e_{2}$ the principal directions of $S$ at $p$

defined by the following equivalent definitions:
## Martin Li def
- $H=\frac{1}{2}\tr S_{p}$
- $K=\det S_{p}$
- $k_{v}=\innerp{\alpha''(0)}{N(p)}{}=\sff_{p}(v,v)$, where $\alpha$ is the regular curve of intersection between $S$ and the oriented plane $P_{v}=\span \set{v,N(p)}$ s.t. $\alpha(0)=p,\alpha'(0)=v$.
- $k_{1},k_{2}$
## doCarmo def
- $k_{n}=k\cos \theta$, $C$ is a regular curve in $S$ passing through $p$, $k$ is the curvature of $C$ at $p$, $n$ is the normal vector to $C$, and $\theta=\arccos \innerp{n}{N(p)}{}$
- $k_{1}=\max \set{k_{n}},k_{2}=\min\set{k_{n}}$, where $\set{k_{n}}$ is the set of all normal curvatures at $p$
- $H=- \dfrac{1}{2}\tr (dN_{p})=\dfrac{k_{1}+k_{2}}{2}$
- $K=\det (dN_{p})=k_{1}k_{2}$
## Lee Man Chun def
- $k_{1}=\max \set{\sff(v,v)\given \norm{v}=1}, k_{2}=\min \set{\sff(v,v)\given \norm{v}=1}$ (consider the diagonal representation of $\sff$ by [[LA T 6.36 (Any symmetric bilinear form on finite-dimensional real inner product spaces is orthogonally diagonalizable)]])
- $H=\dfrac{k_{1}+k_{2}}{2}$
- $K=k_{1}k_{2}$