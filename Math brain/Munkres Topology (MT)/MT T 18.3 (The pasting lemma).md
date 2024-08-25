Book: [[Munkres Topology (MT)]]
# Theorem 18.3 (The pasting lemma)
Let $X=A\cup B$, where $A,B$ are closed in $X$.
Let $f:A\to Y,g:B\to Y$ be continuous.
Suppose $f|_{A\cap B}=g|_{A\cap B}$, that is $f(x)=g(x)$ for all $x\in A\cap B$.
Then $h:X\to Y$ defined by $h(x)=\begin{cases}f(x)&\text{ if }x\in A\\g(x)&\text{ if }x\in B\end{cases}$  is continuous.
#### Proof
Let $C$ be a closed subset of $Y$.
Then $h^{-1}(C)=f^{-1}(C)\cup g^{-1}(C)$.
Since $f,g$ are continuous, we have $f^{-1}(C)$ is closed in $A$ and $g^{-1}(C)$ is closed in $B$.
Since $A,B$ are closed, we have both $f^{-1}(C),g^{-1}(C)$ are closed in $X$.
It fofllows that $h^{-1}(C)$ is closed in $X$.