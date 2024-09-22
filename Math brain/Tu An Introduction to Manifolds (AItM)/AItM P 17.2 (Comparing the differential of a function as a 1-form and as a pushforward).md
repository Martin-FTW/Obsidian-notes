Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 17.2 (Comparing the differential of a function as a 1-form and as a pushforward)
Let $M$ be a manifold and $f\in C^{\infty}(M)$.
Then $\forall p\in M$ and $\forall X_{p}\in T_{p}M$, we have $\displaystyle f\pushforward[,p](X_{p})=(df)_{p}(X_{p})\left.\frac{d}{dt}\right\vert_{f(p)}$.
#### Proof
Since $f\pushforward[,p](X_{p})\in T_{f(p)}\mathbb{R}$ and $\displaystyle \set*{\left.\frac{d}{dt}\right\vert_{f(p)}}$ is a basis for $T_{f(p)}\mathbb{R}$, we have some $a\in \mathbb{R}$ s.t. $\displaystyle f\pushforward[,p](X_{p})=a\left.\frac{d}{dt}\right\vert_{f(p)}$
Thus $a=f\pushforward(X_{p})(t)=X_{p}(t\circ f)=X_{p} f=(df)_{p}(X_{p})$.