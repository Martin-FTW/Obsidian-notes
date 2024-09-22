Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Differential of a map between manifolds)
Let $N,M$ be manifolds.
Let $F:N\to M$ be $C^{\infty}$.
Then $\forall p\in N$, define a linear map $F\pushforward[,p]:T_{p}N\to T_{F(p)}M$ by 
- $\forall X_{p}\in T_{p}N:F\pushforward[,p](X_{p})\in T_{F(p)}M$ is defined by 
	- $\forall f\in C_{F(p)}^{\infty}(M):F\pushforward[,p](X_{p})(f)=X_{p}(f\circ F)\in \mathbb{R}$ 

We call this the differential of $F$ at $p$.