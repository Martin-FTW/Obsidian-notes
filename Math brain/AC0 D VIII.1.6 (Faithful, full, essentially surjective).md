Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Definition VIII.1.6 (Faithful, full, essentially surjective)
Let $\mathsf{C}, \mathsf{D}$ be categories and $\mathscr{F}:\mathsf{C}\to \mathsf{D}$ be a covariant functor.
We call $\mathscr{F}$:
- faithful if the induced function $\mathscr{F}:\hom_{\mathsf{C}}(A,B)\to \hom_{\mathsf{D}}(\mathscr{F}(A),\mathscr{F}(B))$ is injective for any $A,B\in \obj(\mathsf{C})$
- full if the induced function $\mathscr{F}:\hom_{\mathsf{C}}(A,B)\to \hom_{\mathsf{D}}(\mathscr{F}(A),\mathscr{F}(B))$ is surjective for any $A,B\in \obj(\mathsf{C})$
- essentially surjective if $\forall B\in \obj(\mathsf{D}):\exists A\in \obj(\mathsf{C}):B\cong \mathscr{F}(A)$