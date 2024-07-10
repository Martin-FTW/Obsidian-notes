Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Definition (Normal vectors and planes)
## Space curve
Let $\alpha:I\to \mathbb{R}^{3}$ be a regular curve.
Let $s\in I$ s.t. $\alpha$ is $\alpha''(s)\neq 0$.
We call
- $T(s)=\dfrac{\alpha'(s)}{\norm{\alpha'(s)}}$ the unit tangent vector of $\alpha$ at $s$
- $N(s)=\dfrac{\alpha''(s)}{\norm{\alpha''(s)}}$ the normal vector of $\alpha$ at $s$
- $B(s)= T(s)\times N(s)$ the binormal vector of $\alpha$ at $s$
- $\set{T(s),N(s),B(s)}$ the Frenet frame of $\alpha$ at $s$
- $\span \set{T(s),N(s)}$ the osculating plane of $\alpha$ at $s$
- $\span \set{T(s),B(s)}$ the rectifying plane of $\alpha$ at $s$ 
- $\span \set{N(s),B(s)}$ the normal plane of $\alpha$ at $s$
- $\span \set{T(s)}$ the tangent line of $\alpha$ at $s$
- $\span \set{N(s)}$ the principal normal of $\alpha$ at $s$
- $\span \set{B(s)}$ the binormal of $\alpha$ at $s$