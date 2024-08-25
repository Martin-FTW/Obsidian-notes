Book: [[Tu An Introduction to Manifolds (AItM)]]
# Remark (Smooth vector fields have smooth coefficients relative to the standard frame)
Let $M$ be a manifold and $X:M\to M$ be a smooth vector field.
By [[AItM D 12.7 (Vector field on manifold)]], it is smooth as a section on the tangent bundle $\pi:TM \to M$.
Now in a chart $(U,\phi)$ about $p\in M$, we have $\displaystyle X_{p}=\sum a^{i}(p)\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}$, thus $a^{i}$ are functions on $U$.
The chart $(U,\phi)$ also induces a chart $(TU,\tilde{\phi})=(TU,\bar{x}^{1},\dots,\bar{x}^{n},c^{1},\dots,c^{n})$, where $\bar{x}^{i}=\pi \pullback x^{i}=x^{i}\circ \pi$ and $c^{i}$ are defined by $\displaystyle v=\sum c^{i}(v)\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}$.
By comparing coefficients in $\displaystyle X_{p}=\sum a^{i}(p)\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}=\sum c^{i}(X_{p})\left.\frac{ \partial }{ \partial x^{i} }\right\vert_{p}$ for all $p\in U$, we have $a^{i}=c^{i}\circ X$.
Now since $c^{i}$ are smooth by [[AItM P 12.12 (Characterization of smooth sections)]], we have $a^{i}$ are smooth as well.