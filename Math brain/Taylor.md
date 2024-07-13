# Taylor
## Euclidean space
Let $f:\mathbb{R}^n\to\mathbb{R},a=(a_1,\cdots,a_n)\in\mathbb{R^n},d\in \mathbb{Z}_{>0}$
For any $x\in \mathbb{R}^{n}$, define $g_{x}:\cc{0}{1}\to\mathbb{R}$ by $g_{x}(t)=f(a+t(x-a))$ for any $t\in[0,1]$
The taylor polynomial of $f$ at $a$ with degree $d$ is defined as 
$$\begin{align*}
T_d(x)&=\sum_{k=0}^d \frac{g^{(k)}(0)}{k!}=\sum_{k=0}^d\frac{1}{k!}\sum_{i_1,\cdots,i_k\in⟦1,n⟧} \frac{\partial^k f}{\partial x_{i_1}\cdots\partial x_{i_k}}(a)\prod_{\ell=1}^k(x_{i_\ell}-a_{i_\ell})\\
	&=f(a)+\sum_{i=1}^n \frac{\partial f}{\partial x_i}(a)(x_i-a_i)+\frac{1}{2!}\sum_{i=1}^n \sum_{j=1}^n \frac{\partial^2 f}{\partial x_i \partial x_j}(a)(x_i-a_i)(x_j-a_j)+\cdots\\
	&=f(a)+\nabla^T f\vert_a(x-a)+\frac{1}{2}(x-a)^THf\vert_a(x-a)+\cdots
	\end{align*}$$
