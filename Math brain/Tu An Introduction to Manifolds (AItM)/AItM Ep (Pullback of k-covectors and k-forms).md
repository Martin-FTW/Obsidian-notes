Book: [[Tu An Introduction to Manifolds (AItM)]]
# Exposition (Pullback of k-form)
Let $N,M$ be manifolds and $F:N\to M$ be smooth.
At each $p\in N$, the differential $F\pushforward[,p]:T_{p}N\to T_{F(p)}M$ can be pulled back to the codifferential $(F\pushforward[,p])\pullback:A_{k}(T_{F(p)}M)\to A_{k}(T_{p}N)$.
Define $F\pullback\coloneqq(F\pushforward[,p])\pullback:\bigwedge^{k}(T_{F(p)}^*M)\to \bigwedge^{k}(T_{p}^*N)$.
Then for a $k$-covector $\omega_{F(p)}$ at $F(p)$, its pullback $F\pullback(\omega_{F(p)})$ is a $k$-covector at $p$ in $N$ given by $F\pullback(\omega_{F(p)})(v_{1},\dots,v_{k})=\omega_{F(p)}(F\pushforward[,p]v_{1},\dots,F\pushforward[,p]v_{k})$ for all $v_{i}\in T_{p}N$.
Finally, for a $k$-form $\omega$ on $M$, its pullback $F\pullback \omega$ is the $k$-form on $N$ defined pointwisely by $(F\pullback \omega)_{p}=F\pullback (\omega _{F(p)})$ for all $p\in N$.
i.e. $(F\pullback \omega)_{p}(v_{1},\dots,v_{k})=(F\pullback(\omega_{F(p)}))(v_{1},\dots,v_{k})=\omega_{F(p)}(F\pushforward[,p]v_{1},\dots,F\pushforward[,p]v_{k})$ for all $v_{i}\in T_{p}N$.