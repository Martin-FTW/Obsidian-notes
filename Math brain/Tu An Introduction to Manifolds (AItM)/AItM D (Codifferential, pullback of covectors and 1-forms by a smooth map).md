Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Codifferential, pullback of covectors and 1-forms by a smooth map)
Let $N,M$ be manifolds and $p\in N$.
Let $F:N\to M$ be a smooth map.
Note that the differential $F\pushforward[,p]:T_{p}N\to T_{F(p)}M$ pushes forward vectors at $p$ from $N$ to $M$.
Define the codifferential $F\pullback\coloneqq(F\pushforward[,p])\dual:T_{F(p)}^*M\to T_{p}^*N$, which pulls back a covector at $F(p)$ from $M$ to $N$.
For any covector $\omega_{F(p)}\in T_{F(p)}^*M$ at $F(p)$ and tangent vector $X_{p}\in T_{p}N$ at $p$, we have $F\pullback(\omega_{F(p)})(X_{p})=((F\pushforward[,p])\dual \omega_{F(p)})(X_{p})=\omega_{F(p)}(F\pushforward[,p]X_{p})$.
We call $F\pushforward(\omega_{F(p)})$ the pullback of $\omega_{F(p)}$ by $F$.
Unlike vector fields in [[AItM Eg 14.15 (Pushforward by a diffeomorphism)]], we can pullback every covector field by a smooth map.
Let $\omega$ be a $1$-form on $M$.
Define $F\pullback \omega$ by $(F\pullback \omega)_{p}=F\pullback(\omega_{F(p)})$ for all $p\in N$.
Then we have $(F\pullback \omega)_{p}(X_{p})=\omega_{F(p)}(F\pushforward(X_{p}))$.