Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Definition VIII.1.1 (Functor, presheaf)
Let $\mathsf{C},\mathsf{D}$ be categories.
A covariant functor $\mathscr{F}:\mathsf{C}\to \mathsf{D}$ is the (class) functions:
- $\obj \mathsf{C}\to \obj \mathsf{D}$
- $\hom_{\mathsf{C}}(A,B)\to \hom_{\mathsf{D}}(\mathscr{F}(A),\mathscr{F}(B))$ for each $A,B\in \obj\mathsf{C}$

that satisfies:
- $\forall A\in \obj \mathsf{C}:\mathscr{F}(1_{A})=1_{\mathscr{F}(A)}$
- $\forall \alpha\in \hom_{\mathsf{C}}(A,B),\beta\in \hom_{\mathsf{C}}(B,C):\mathscr{F}(\beta \circ \alpha)=\mathscr{F}(\beta)\circ \mathscr{F}(\alpha)$

A contravariant functor $\mathscr{G}:\mathsf{C}\to \mathsf{D}$ is defined as a covariant functor $\mathsf{C}^{op}\to \mathsf{D}$.
Note that $\mathscr{G}(\beta \circ \alpha)=\mathscr{G}(\alpha)\circ \mathscr{G}(\beta)$, the order is swapped

A covaraiant functor preserve arrows in a diagram while a contravariant functor reverses all arrows in a diagram.

A contravariant functor $\mathsf{C}\to \mathsf{Set}$ is called a presheaf of sets on $\mathsf{C}$.