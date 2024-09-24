Book: [[Tu An Introduction to Manifolds (AItM)]]
# Definition (Differential forms in Euclidean space)
Let $U\subseteq \mathbb{R}^{n}$ be open.
Let $\displaystyle \omega:U\to \coprod_{p\in U}A_{k}(T_{p}\mathbb{R}^{n})$ be a function denoted by $\omega(p)=\omega _{p}$.
We call $\omega$ a $k$-form if $\forall p\in U:\omega _{p}\in A_{k}(T_{p}\mathbb{R}^{n})$.
When $k=0$, we have $A_{0}(T_{p}\mathbb{R}^{n})=\mathbb{R}$, thus $0$-forms are functions on $U$.
When $k=1$, we have $A_{1}(T_{p}\mathbb{R}^{n})=T_{p}^*\mathbb{R}^{n}$, thus $1$-form are covector fields on $U$.
Since a basis for $A_{k}(T_{p}\mathbb{R}^{n})$ is $dx_{p}^{I}=dx_{p}^{i_{1}}\wedge\dots \wedge dx_{p}^{i_{k}},1\leq i_{1}<\cdots<i_{k}\leq n$, we have the linear combination $\omega _{p}=\sum_{I} a_{I}(p)dx_{p}^{I}$, summing over all strictly increasing multi-indices for any $p\in U$.
Thus a $k$-form $\omega$ on $U$ is a linear combination $\omega=\sum a_{I}dx^{I}$, where $a_{I}:U\to \mathbb{R}$ are the coefficient functions.
We call $\omega$ $C^{\infty}$ on $U$ if all coefficients $a_{I}$ are $C^{\infty}$ on $U$.
Denote by $\Omega ^{k}(U)$ the vector space of all $C^{\infty}$ $k$-forms on $U$.
Define the wedge product of two differential forms by: $(\omega \wedge \uptau)_{p}=\omega _{p}\wedge\uptau _{p}$ for all $p\in U$.
If $\omega=\sum a_{I}dx^{I},\uptau=\sum b_{J}dx^{J}$, then $\omega \wedge\uptau=\sum (a_{I}b_{J})dx^{I}\wedge dx^{J}$.
Define the graded algebra $\Omega ^*(U)=\bigoplus \Omega ^{k}(U)$. With the grading $\wedge$, $\Omega ^*(U)$ is an anticommutative graded algebra over $\mathbb{R}$.