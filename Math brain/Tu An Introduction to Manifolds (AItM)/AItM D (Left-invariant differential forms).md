Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Left-invariant differential forms)
Let $G$ be a Lie group.
Let $\omega$ be a $k$-form on $G$.
We say that $\omega$ is left-invariant if $\forall g\in G:\ell_{g}\pullback \omega=\omega$.
That is, $\forall g,x\in G:\ell_{g}\pullback(\omega_{gx})=\omega_{x}$.
In this case, $\omega$ is uniquely determined by its value at identity by $\omega_{g}=\ell_{g^{-1}}\pullback(\omega_{e})$ for all $g\in G$.
The vector space of left-invariant $k$-forms on $G$ is denoted by $\Omega^{k}(G)^{G}$.
Since $\Omega^{k}(G)^{G}\to \bigwedge^{k}(\mathfrak{g}\dual),\omega \mapsto \omega_{e}$ has inverse defined by $\omega_{g}=\ell_{g^{-1}}\pullback(\omega_{e})$, it is an isomorphism, thus $\dim \Omega^{k}(G)^{G}=\binom nk$ 