Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 17.15 (1-form on circle)
Consider the immersed submanifold $i:\mathbb{S}^{1}\to \mathbb{R}^{2}$.
The velocity vector field of $c(t)=(x,y)=(\cos t,\sin t)$ is $c'(t)=(-\sin t,\cos t)=(-y,x)$.
Thus $\displaystyle X=-y\frac{ \partial }{ \partial x }+x\frac{ \partial }{ \partial y }$ is a smooth vector field on $\mathbb{S}^{1}$. 
Now $\displaystyle i\pushforward(X_{p})=-y\left.\frac{ \partial }{ \partial x }\right\vert_{p}+x\left.\frac{ \partial }{ \partial y }\right\vert_{p}\in T_{p}\mathbb{R}^{2}$.
Goal: Find $\omega=adx+bdy$ on $S^{1}$ s.t. $\omega(X)\equiv 1$.
#### Proof
In $\mathbb{R}^{2}$, we have
$\displaystyle \omega(X)=(adx+bdy)\left( -y\frac{ \partial }{ \partial x }+x\frac{ \partial }{ \partial y } \right)=-ay+bx$.
Take $a=-y,b=x$. Then $-ay+bx=x^{2}+y^{2}=1$.
