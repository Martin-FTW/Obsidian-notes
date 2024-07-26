Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Tangent space, tangent vector, directional derivative in Euclidean space)
Let $p\in \mathbb{R}^{n}$.
An arrow enamating from $p$ is called a tangent vector at $p$ in $\mathbb{R}^{n}$.
The set of all tangent vectors at $p$ is called the tangent space $T_{p}\mathbb{R}^{n}$ of $\mathbb{R}^{n}$ at $p$.
The disjoint union $\displaystyle T\mathbb{R}^{n}=\coprod_{p\in U}T_{p}\mathbb{R}^{n}$ is called the tangent bundle of $\mathbb{R}^{n}$.
If $\set{e_{i}}$ is a standard basis for $T_{p}\mathbb{R}^{n}$, we write $v=\sum v^{i}e_{i}$.
Now suppose $f$ is $C^{\infty}$ in a nbhd of $p$ and $v\in T_{p}\mathbb{R}^{n}$.
The directional derivative of $f$ in the direction of $v$ at $p$ is defined to be $$D_{v}f=\lim_{t\to 0}\frac{f(c(t))-f(p)}{t}=\left.\frac{d}{dt}\right\vert_{t=0}f(c(t))=(f\circ c)'(0)\in \mathbb{R}$$, where $c(t)=(p^{1}+tv^{1},\dots,p^{n}+tv^{n})$.
Note that by chain rule,
$$D_{v}f=\sum \frac{dc^{i}}{dt}(0)\frac{ \partial f }{ \partial x^{i} }(p)=\sum v^{i}\frac{ \partial f }{ \partial x^{i} }(p)$$
Thus we write $\displaystyle D_{v}=\sum v^{i}\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}$ as a function $f\mapsto D_{v}f$.