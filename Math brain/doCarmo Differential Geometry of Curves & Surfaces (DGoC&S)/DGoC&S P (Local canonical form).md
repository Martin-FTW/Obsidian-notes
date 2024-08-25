Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Proposition (Local canonical form)
Let $\alpha:I\to \mathbb{R}^{3}$ be a curve pbal without singular points of order $1$.
Suppose $0\in I$ (for any $s_{0}\in I$, translate the curve $s_{0}\to0$)
Then $\alpha(s)=\left( s-\frac{1}{6}k(0)^{2}s^{3}, \frac{1}{2}k(0)s^{2}+ \frac{1}{6}k'(0)s^{3},-\frac{1}{6}k(0)\uptau(0) s^{3} \right)+o(s^{3})$, where $\alpha(s_{0})$ is the origin and the Frenet frame of $\alpha$ at $s_{0}$ is the basis.
We call this the local canonical form of $\alpha$ at $s_{0}$.
#### Proof
By Taylor's theorem, we have $\alpha(s)=\alpha(0)+\alpha'(0)s+ \frac{\alpha'(0)}{2}s^{2}+\frac{\alpha'''(0)}{6}s^{3}+o(s^{3})$.
Now $\alpha'(0)=T(0), \alpha''(0)=k(0)N(0)$, and $\alpha'''(0)=k'(0)N(0)+k(0)N'(0)=(k'N-k^{2}T-k\uptau B)(0)$.
Hence $$\begin{align}
\alpha(s)-\alpha(0)&=T(0)s+\frac{(kN)(0)}{2}s^{2}+ \frac{(k'N-k^{2}T-k\uptau B)(0)}{6}s^{3}+o(s^{3}) \\
&=\left( s-\frac{1}{6}k^{2}s^{3} \right)T(0)+ \left( \frac{1}{2}ks^{2}+ \frac{1}{6}k's^{3} \right)N(0)-\frac{1}{6}k\uptau s^{3}B(0)+o(s^{3})
\end{align}$$

Now let $\alpha(0)$ be the origin and the Frenet frame $\set{T(0),N(0),B(0)}$ as basis.
Then in this new system, the basis representation gives the local canonical form $\alpha(s)=\left( s-\frac{1}{6}k(0)^{2}s^{3}, \frac{1}{2}k(0)s^{2}+ \frac{1}{6}k'(0)s^{3},-\frac{1}{6}k(0)\uptau(0) s^{3} \right)+o(s^{3})$.
