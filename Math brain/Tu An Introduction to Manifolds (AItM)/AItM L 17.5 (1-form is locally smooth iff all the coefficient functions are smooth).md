Book: [[Tu An Introduction to Manifolds (AItM)]]
# Lemma 17.5 (1-form is locally smooth iff all the coefficient functions are smooth)
Let $M$ be a manifold and $(U,\phi)=(U,x^{1},\dots,x^{n})$ be a chart on $M$.
Let $\omega:M\to T^*M$ be a smooth $1$-form, i.e. it is smooth as a section of the cotangent bundle $\pi:T^*M\to M$.
Then we have $\omega_{p}=\sum a_{i}(p)dx^{i}\vert_{p}$.
In the induced chart $(T^*U,\tilde{\phi})=(T^*U,\bar{x}^{1},\dots,\bar{x}^{n},c_{1},\dots,c_{n})$, we have $\omega_{p}=\sum c_{i}(\omega_{p})dx^{i}\vert_{p}$.
Note that the coefficient functions are $a_{i}(p)=c_{i}(\omega_{p})=(c_{i}\circ \omega)(p)$.
Then we have $\omega|_{U}$ is smooth iff $a_{i}$ are all smooth.
#### Proof
From [[AItM P 12.12 (Characterization of smooth sections)]]
