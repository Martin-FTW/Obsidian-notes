Book: [[Tu An Introduction to Manifolds (AItM)]]
# Exercise 14.11 (Lie bracket satisfies Jacobi identity)
Let $M$ be a manifold and $X,Y,Z$ be vector fields on $M$.
Then $\displaystyle \sum_{cyc}[X,[Y,Z]]=0$.
#### Proof
$$\begin{align}
\sum _{cyc}[X,[Y,Z]]&=\sum_{cyc}[X,YZ-ZY] \\
&=\sum_{cyc}X(YZ-ZY)-(YZ-ZY)X \\
&=\sum_{cyc}XYZ-XZY-YZX+ZYX \\
&=\sum_{cyc}XYZ-\sum_{cyc}XZY-\sum_{cyc}YZX+\sum_{cyc}ZYX \\
&=\sum_{cyc}XYZ-\sum_{cyc}ZYX-\sum_{cyc}XYZ+\sum_{cyc}ZYX \\
&=0
\end{align}$$