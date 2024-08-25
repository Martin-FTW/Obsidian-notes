Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition 10.2 (Covariant functor)
Let $\mathcal{C},\mathcal{D}$ be categories.
A covariant functor $\mathcal{F}$ from $\mathcal{C}$ to $\mathcal{D}$ is a map with
1. $\forall$ object $A$ in $\mathcal{C}$, $\exists!$ object $\mathcal{F}(A)$ in $\mathcal{D}$
2. $\forall$ morphism $f:A\to B$ in $\mathcal{C}$, $\exists!$ morphism $\mathcal{F}(f):\mathcal{F}(A)\to \mathcal{F}(B)$ in $\mathcal{D}$

such that
1. $\mathcal{F}(\mathbb{1}_{A})=\mathbb{1}_{\mathcal{F}(A)}$
2. $\mathcal{F}(f\circ g)=\mathcal{F}(f)\circ \mathcal{F}(g)$