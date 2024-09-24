Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 17.8 (Linearity of a 1-form over functions and on the vector space of smooth vector fields)
Let $M$ be a manifold and $\omega$ be a $1$-form.
Use the notation in [[AItM Ep (Induced linear map on vector fields by 1-form)]].
Then $\forall$ vector field $X$ on $M$ and function $f:M\to \mathbb{R}$, we have $\omega(fX)=f\omega(X)$, i.e. $\omega(fX)_{p}=f(p)\omega(X)_{p}$.

Further suppose that $\omega$ is smooth.
Since $\omega(X+Y)=\omega(X)+\omega(Y)$ is automatic, this shows that the map $\mathfrak{X}(M)\to C^{\infty}(M),X\mapsto \omega(X)$ is not only $\mathbb{R}$-linear as a vector space homomorphism, but also $C^{\infty}(M)$-linear as a module homomorphism
#### Proof
Let $p\in M$.
Then $\omega(fX)_{p}=\omega_{p}(f(p)X_{p})=f(p)\omega_{p}(X_{p})=(f\omega(X))_{p}$