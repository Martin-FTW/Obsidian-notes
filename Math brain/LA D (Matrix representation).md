Book: [[Friedberg Linear Algebra (LA)]]
# Definition (Matrix representation)
Let $V,W$ be finite-dimensional vector spaces.
Let $\set{v_{j}}_{j=1}^{n}$ be an ordered basis for $V$ and $\set{w_{i}}_{i=1}^{m}$ be an ordered basis for $W$.
Let $T:V\to W$ be linear.
Then $\forall j\in\ii{1}{n},i\in\ii{1}{m}:\exists!a_{ij}\in F$ s.t. $$T(v_{j})=\sum_{i=1}^{m}a_{ij}w_{i}\text{ for all }j\in\ii{1}{n}$$
We call $[T]_{\beta}^{\gamma}\coloneqq(a_{ij})$ the matrix representation of $T$ in the ordered bases $\beta,\gamma$.
If $V=W$ and $\beta=\gamma$ then we write $[T]_{\beta}\coloneqq(a_{ij})$

Note that the $j$th column of $[T]_{\beta}^{\gamma}$ is $[T(v_{j})]_{\gamma}$.
Note that if $U:V\to W$ is linear s.t. $[U]_{\beta}^{\gamma}=[T]_{\beta}^{\gamma}$ then $U=T$.