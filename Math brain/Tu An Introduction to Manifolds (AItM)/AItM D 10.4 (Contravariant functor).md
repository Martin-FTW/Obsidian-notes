Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition 10.4 (Contravariant functor)
Let $\mathcal{C},\mathcal{D}$ be categories.
A contravariant functor $\mathcal{F}$ from $\mathcal{C}$ to $\mathcal{D}$ is a map with
1. $\forall$ object $A$ in $\mathcal{C}$, $\exists!$ object $\mathcal{F}(A)$ in $\mathcal{D}$
2. $\forall$ morphism $f:A\to B$ in $\mathcal{C}$, $\exists!$ morphism $\mathcal{F}(f):\mathcal{F}(B)\to \mathcal{F}(A)$ in $\mathcal{D}$

such that
1. $\mathcal{F}(\mathbb{1}_{A})=\mathbb{1}_{\mathcal{F}(A)}$
2. $\mathcal{F}(f\circ g)=\mathcal{F}(g)\circ \mathcal{F}(f)$