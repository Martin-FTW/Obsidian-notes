Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 17.14 (Restriction of 1-forms is the pullback of inclusion)
Let $M$ be a manifold and $S$ be an immersed submanifold with inclusion $i:S\to M$.
Let $\omega$ be a $1$-form on $M$.
Then the restriction $1$-form $\omega \vert_{S}=i\pullback \omega$.
#### Proof
Let $p\in S,v\in T_{p} S$.
$(i\pullback \omega)_{p}(v)=\omega_{i(p)}(i\pushforward(v))=\omega_{p}(v)=(\omega \vert_{S})_{p}(v)$.