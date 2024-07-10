Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Definition (Limit, colimit)
Let $\mathscr{F}:\mathsf{I}\to \mathsf{C}$ be a covariant functor.
Let $L\in \obj \mathsf{C}$ and let $\lambda_{I}\in \hom_{\mathsf{C}}(L,\mathscr{F}(I))$ for each $I\in \obj(\mathsf{I})$
We say that $L$ is the limit of $\mathscr{F}$ if
1. $\forall$ morphism $\alpha:I\to J$ in $\mathsf{I}$, $\lambda_{J}=\mathscr{F}(\alpha)\circ \lambda_{I}$
2. $L$ is final w.r.t. this property:
	- $\forall M\in \obj(\mathsf{C})$ and $\mu_{I}$ defined similarly above that also satisfies (1), $\exists! \sigma:M\to L$ that makes all relevant diagrams commute.