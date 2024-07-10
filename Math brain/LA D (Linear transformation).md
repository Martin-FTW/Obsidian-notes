Book: [[Friedberg Linear Algebra (LA)]]
# Definition (Linear transformation)
Let $F$ be a [[Field]] and $V,W$ be [[Vector space]]s over $F$.
Let $T:V\to W$ be a [[Function|Function]].
We say $T$ is a linear transformation if the following statements hold:
1. $\forall x,y\in V:T(x+y)=T(x)+T(y)$
2. $\forall c\in F, x\in V:T(cx)=cT(x)$.

One can combine both statements into the following:
- $\forall c\in F, x,y\in V:T(cx+y)=cT(x)+T(y)$

Note that unlike functions, we sometimes write $T(v)$ as simply $Tv$.
Therefore, for linear transformations $T:U\to V, S: V\to W$, their composition would be $ST:U\to W$ since $(S\circ T)(u)=S(Tu)=STu=ST(u)$