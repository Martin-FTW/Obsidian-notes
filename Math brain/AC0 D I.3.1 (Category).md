Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Definition I.3.1 (Category)
A category $\mathsf{C}$ consists of
- a class $\obj(\mathsf{C})$ of objects of the category, and
- $\forall A,B\in \obj(\mathsf{C})$, a set $\hom_{\mathsf{C}}(A,B)$ of morphisms, satisfying:
	- $\forall f\in \hom_{\mathsf{C}}(A,B),g\in \hom_{\mathsf{C}}(B,C):\exists gf\in \hom_{\mathsf{C}}(A,C)$.
	- $(hg)f=h(gf)$ for any compatible morphisms $f,g,h$
	- $\forall A\in \obj \mathsf{C}:\exists 1_{A}\in \hom_{\mathsf{C}}(A,A):f 1_{A}=f,1_{A}g=g$ for any compatible morphisms $f,g$.

If $\mathsf{C}$ is a category, we further denote:
- $\end_{\mathsf{C}}(A)\coloneqq\hom_{\mathsf{C}}(A,A)$ the set of endomorphisms on $A$
- $f:A\to B$ instead of $f\in \hom_{\mathsf{C}}(A,B)$.

A diagram of morphisms is a collection of objects of $\mathsf{C}$ with arrows between them representing morphisms.
A diagram is said to commute if all ways of composing morphisms between two objects are equal.