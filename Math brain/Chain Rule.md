# Chain rule

## Euclidean
### n,m,k
Let $f:\mathbb{R}^n\to\mathbb{R}^m,g:\mathbb{R}^m\to\mathbb{R}^k,{a}\in\mathbb{R}^n$.
Suppose ${f}$ is differentiable at ${a}$ and ${g}$ is differentiable at ${f}({a})$.
Then ${g}\circ{f}$ is differentiable at ${a}$ and $D({g}\circ {f})|_{a}=D{g}|_{{f}({a})}\circ D{f}|_{a}$ on $\mathbb{R}^{n}$.
The matrix representation in $\set{e_{i}}$ gives 
- $J_{g\circ f}(a)=J_{g}(f(a))J_{f}(a)$
- $J_{g\circ f}=(J_{g}\circ f)\cdot J_{f}$ on $\set{a}$.
- $\dfrac{ \partial (y_{1},\dots,y_{k}) }{ \partial (x_{1},\dots,x_{n}) }=\dfrac{ \partial (y_{1},\dots,y_{k}) }{ \partial (u_{1},\dots,u_{m}) }\dfrac{ \partial (u_{1},\dots,u_{m}) }{ \partial (x_{1},\dots,x_{n}) }$, where $y=g(u)=g(f(x))$
- $\displaystyle \dfrac{ \partial (y_{1},\dots,y_{k}) }{ \partial x_{i} }=\dfrac{ \partial (y_{1},\dots,y_{k}) }{ \partial (u_{1},\dots,u_{m}) }\dfrac{ \partial (u_{1},\dots,u_{m}) }{ \partial x_{i} }=\sum_{j=1}^{m}\dfrac{ \partial (y_{1},\dots,y_{k}) }{ \partial u_{j} }\dfrac{ \partial u_{j} }{ \partial x_{i} }$ for all $i\in\ii{1}{n}$, where $y=g(u)=g(f(x))$
### k=1
Let $f:\mathbb{R}^n\to\mathbb{R}^m,\varphi:\mathbb{R}^m\to\mathbb{R},{a}\in\mathbb{R}^n$.
Suppose ${f}$ is differentiable at ${a}$ and $\varphi$ is differentiable at $f({a})$.
Then $\varphi\circ{f}$ is differentiable at ${a}$ and 
- ${\nabla}\transpose (\varphi\circ {f})|_{a}=({\nabla}\transpose \varphi|_{{f}({a})})(D{f}|_{a})$
- $\displaystyle \frac{\partial\varphi}{\partial x_i}=\sum_{j=1}^m \frac{\partial\varphi}{\partial u_j}\frac{\partial u_j}{\partial x_i}$ for all $i\in\ii{1}{n}$
#### k=n=1
Let $v:\mathbb{R}\to\mathbb{R}^m,\varphi:\mathbb{R}^m\to\mathbb{R},t_0\in\mathbb{R}$.
Suppose ${v}$ is differentiable at $t$ and $\varphi$ is differentiable at ${v}(t_0)$.
Then $\varphi\circ{v}$ is differentiable at $t$ and
- $(\varphi\circ {v})'(t_0)=[{\nabla}\transpose \varphi({v}(t_0))]{v}'(t_0)$
- $\displaystyle \left.\frac{d(\varphi\circ {v})}{dt}\right\vert_{t_0}=({\nabla}\transpose \varphi\vert_{{v}(t_0)})\left.\frac{dv}{dt}\right\vert_{t_0}$
- $\displaystyle \frac{d\varphi}{dx}=\sum_{j=1}^m \frac{\partial\varphi}{\partial v_i}\frac{dv_i}{dx}$
