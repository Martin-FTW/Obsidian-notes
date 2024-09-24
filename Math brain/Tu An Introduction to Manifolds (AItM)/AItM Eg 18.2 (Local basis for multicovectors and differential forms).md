Book: [[Tu An Introduction to Manifolds (AItM)]]
# Example 18.2 (Local basis for multicovectors and differential forms)
Let $M$ be a manifold and $(U,\phi)=(U,x^{1},\dots,x^{n})$ be a chart.
Now $\forall p\in U$, we have a basis $\displaystyle \set*{\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}}$ for $T_{p}U$.
Thus $\set{(dx^{i})_{p}}$ is the dual basis for $T_{p}^*U$ by [[AItM P 17.3 (Dual basis for cotangent space)]].
Note that $dx^{i}$ are $1$-forms on $U$.
Now all the $(dx^{i_{1}})_{p}\wedge \cdots\wedge(dx^{i_{k}})_{p}$ where $1\leq i_{1}<\cdots<i_{k}\leq n$ forms a basis for $\bigwedge^{k}(T_{p}^*U)$ by [[AItM P 3.29 (Basis for multicovectors)]]
In multi-indices, first let $\begin{align}\mathcal{J}_{k,n}&=\set{I\in\ii{1}{n}^{k}\given I\text{ is strictly increasing}}\\&=\set{I=(i_{1},\dots,i_{k})\given 1\leq i_{1}<\cdots<i_{k}\leq n}\end{align}$
Then we have $\set{(dx^{I})_{p}\given I\in \mathcal{J}_{k,n}}$ is a basis for $\bigwedge^{k}(T_{p}^*U)$.
Now let $\omega$ be a $k$-form on $U$.
Then at each $p\in U$ we have $\displaystyle \omega_{p}=\sum a_{i_{1},\dots,i_{k}}(p)(dx^{i_{1}})_{p}\wedge \cdots\wedge(dx^{i_{k}})_{p}$
Thus as functions on $U$ we have $\displaystyle \omega=\sum_{I\in \mathcal{J_{k,n}}}a_{I}dx^{I}=\sum a_{i_{1},\dots,i_{k}}dx^{i_{1}}\wedge \cdots\wedge dx^{i_{k}}$.

Note that writing $\partial_{J}=(\partial_{j_{1}},\dots,\partial_{j_{k}})=\left( \frac{ \partial }{ \partial x^{j_{1}} },\dots,\frac{ \partial }{ \partial x^{j_{k}} } \right)$, we have $dx^{I}(\partial_{J})=\delta_{J}^{I}=[I=J]$.
