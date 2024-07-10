Book: [[MATH3030]]
# Proposition (Group action is equivalent to group homo to sym group)
Let $G$ be a group and $X$ be a set.
Then an action of $G$ on $X$ is equivalent to a group homomorphism $\rho:G\to S_{X}$.
#### Proof
Define $\rho(g)(x)=gx$ for any $g\in G, x\in X$.
Now let $g\in G$. we show $\rho(g)\in S_{X}$:
Injective: $\forall x,y\in X$, if $gx=gy$ then $g^{-1}(gx)=g^{-1}(gy)$, thus $x=y$.
Surjective: $\forall x\in X$, we have $g^{-1}x\in X$ and $\rho(g)(g^{-1}x)=x$. 
Now $\rho$ is well-defined, it remains to show that it is a homormophism:
Let $g,g'\in G,x\in X$.
Then $\rho(gg')(x)=gg'x=g\rho(g')(x)=\rho(g)(\rho(g')(x))=(\rho(g)\circ \rho(g'))(x)$
Hence $\rho(gg')=\rho(g)\circ \rho(g')$.
It follows that $\rho$ is a group homomorphism.