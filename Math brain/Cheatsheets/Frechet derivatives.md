# Derivatives
## Exterior derivative
Let $M$ be a Manifold.
Let $d:\Omega(M)\to \Omega(M)$ be a Linear operator on the graded algebra of Differential forms.
We call $d$ an exterior derivative if 
1. $\forall \omega \in \Omega^{k}(M): d\omega \in\Omega^{k+1}(M)$.
2. $\displaystyle\forall f\in \Omega^{0}(M):d f=\nabla f\cdot d x=\sum_{i=1}^{n}\frac{ \partial f }{ \partial x_{i} }d x_{i}$
3. $d \circ d\equiv0$
4. $\forall\omega \in\Omega^{k}(M),\eta \in\Omega^{\ell}(M): d(\omega \wedge\eta)=d\omega \wedge\eta+(-1)^{k}\omega \wedge d \eta$
## Frechet derivative
### V, W normed
Let $V,W$ be normed vector spaces.
Let $U\subseteq V$ be open in the metric topology.
Let $f:U\to W$ be a function.
We say that $f$ is Frechet-differentiation at $a\in U$ if
- $\exists$ bounded $Df(a)\in \mathcal{L}(V,W)$ s.t. $0=\begin{cases}\displaystyle \lim_{x\to a} \frac{\norm{f(x)-f(a)-Df(a)(x-a)}_{W}}{\norm{x-a}_{V}}\\\displaystyle \lim_{h\to 0_{V}} \frac{\norm{f(a+h)-f(a)-Df(a)(h)}_{W}}{\norm{h}_{V}}\end{cases}$

Now suppose $f$ is differentiable on $U$. Then $Df:U\to \mathcal{L}(V,W)$
$\forall k\in \mathbb{Z}_{>0}$, we define $D^{k}f(a)=D(D^{k-1}f)(a)\in \mathcal{L}(V,\mathcal{L}^{k-1}(V,W))\cong \mathcal{L}^{k}(V,W)$.
Examples: $D^{2}f(a)(x,y),D^{3}f(a)(x,y,z)$ etc.
### V, W Euclidean
#### n, m
Restrict $V\cong \mathbb{R}^{n},W\cong\mathbb{R}^{m}$ to be finite dimensional.
Let $U\subseteq \mathbb{R}^{n}$ be an open set.
Let $f:U\to \mathbb{R}^{m}$ be a function.
We say that $f$ is differentiable at $a\in U$ if
- $\exists Df(a)\in \mathcal{L}(\mathbb{R}^{n},\mathbb{R}^{m})$ s.t. $0=\begin{cases}\displaystyle \lim_{x\to a} \frac{\norm{f(x)-f(a)-Df(a)(x-a)}}{\norm{x-a}}\\\displaystyle \lim_{h\to \vec{0}} \frac{\norm{f(a+h)-f(a)-Df(a)(h)}}{\norm{h}}\end{cases}$

Let $\beta,\gamma$ be the standard ordered bases for $\mathbb{R}^{n},\mathbb{R}^{m}$ respectively.
The matrix representation of $Df(a)$ under $\beta,\gamma$ is called the Jacobian matrix, defined by
- $$\begin{align}
Jf(a)\coloneqq[Df(a)]_{\beta}^{\gamma}&=\left[\frac{\partial f_i}{\partial x_j}(a)\right]_{ij}=\begin{bmatrix}
\frac{\partial f}{\partial x_1}(a) & \cdots & \frac{\partial f}{\partial x_n}(a)
\end{bmatrix}\\
&=
\begin{bmatrix}
\nabla\transpose f_1(a) \\
\vdots \\
\nabla\transpose f_m(a) 
\end{bmatrix}
=
\begin{bmatrix}
\frac{\partial f_1}{\partial x_1}(a) & \cdots & \frac{\partial f_1}{\partial x_n}(a) \\
\vdots & \ddots & \vdots \\
\frac{\partial f_m}{\partial x_1}(a) & \cdots & \frac{\partial f_m}{\partial x_n}(a) 
\end{bmatrix}
\end{align}$$

Now suppose $f$ is differentiable on $U$. Then $Df:U\to \mathcal{L}(\mathbb{R}^{n},\mathbb{R}^{m})\cong \mathbb{R}^{nm}$
$\forall k\in \mathbb{Z}_{>0}$, we define $D^{k}f(a)=D(D^{k-1}f)(a)\in \mathcal{L}(V,\mathcal{L}^{k-1}(\mathbb{R}^{n},\mathbb{R}^{m}))\cong \mathcal{L}^{k}(\mathbb{R}^{n},\mathbb{R}^{m})\cong\mathbb{R}^{n^{k}m}$.
#### n=m=1
Restrict $n=m=1$
Let $I\subseteq \mathbb{R}$ be an open interval.
Let $f:I\to \mathbb{R}$ be a function.
We say that $f$ is differentiable at $a\in I$ if 
- $f'(a)\coloneqq\displaystyle \lim_{x\to a} \frac{f(x)-f(a)}{x-a}=\lim_{h\to 0} \frac{f(x+h)-f(x)}{h}$ exists.

$\forall k\in \mathbb{Z}_{>0}$, we define $f^{(k)}(a)\coloneqq f^{(k-1)}(a)$ if it exists.
Note that this is a special case of derivatives in Euclidean space by letting $n=m=1$.
Since $\dim_{\mathbb{R}}\mathcal{L}(\mathbb{R},\mathbb{R})=1\implies \mathcal{L}(\mathbb{R},\mathbb{R})=\span \set{\id_{\mathbb{R}}}=\set{c\cdot \id_{\mathbb{R}}}_{c\in \mathbb{R}}$, we can represent all orders of derivatives as a constant $f^{(k)}(a)$.
## Manifold differentials
### General

### Euclidean
Let $U\subseteq \mathbb{R}^{n}$ be open and $p\in U$.
Let $f:U\to \mathbb{R}^{m}$ be $C^{1}$.
Let $df_{p}:\mathbb{R}^{n}\to \mathbb{R}^{m}$ be defined by $\forall w\in \mathbb{R}^{n}:df_{p}(w)\coloneqq (f\circ \alpha)'(0)$ where $\alpha:(-\varepsilon,\varepsilon)\to U$ is a differentiable curve s.t. $\alpha(0)=p,\alpha'(0)=w$. 

We call $df_{p}$ the differential of $f$ at $p$.
Note that $df_{p}$ is a linear map independent of choice of $\alpha$.