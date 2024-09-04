Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 14.15 (Pushforward by a diffeomorphism)
Let $N,M$ be manifolds and $F:N\to M$ be a smooth map.
For any $X_{p}\in T_{p}N$, we call $F_{*}X_{p}$ the pushforward of $X_{p}$ at $p$.
Now let $X$ be a vector field on $N$.
The pushforward is not well-defined on $X$ since any distinct $p,q\in N$ with $F(p)=F(q)$ need not have $F_{*}(X_{p})=F_{*}(X_{q})$.
However, further suppose $F$ is a diffeomorphism.
Then the pushforward $F_{*}X:TN\to TM$ defined by $(F_{*}X)_{F(p)}=F_{*,p}(X_{p})$ is a well-defined vector field on $M$. 
Then the vector field $X$ is $F$-related to $F_{*}X$. 