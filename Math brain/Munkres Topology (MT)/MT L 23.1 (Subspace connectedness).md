Book: [[Munkres Topology (MT)]]
# Lemma 23.1 (Subspace connectedness)
Let $Y$ be a subspace of $X$.
Then $Y$ is connected iff there exists no separation of $Y$ in $X$.

#### Proof
$(\implies):$ Suppose $Y$ is connected.
Let $U,V$ be a separation, thus both nonempty proper clopen sets in $Y$.
Now $U=\cl_{Y}(U)=\cl_{X}(U)\cap Y$.
Thus $\cl_{X}(U)\cap V=\cl_{X}(U)\cap Y\setminus U=U\setminus U=\emptyset$.
Hence $V$ contains no limit points of $U$, and vice versa.
$(\impliedby):$
Let $A,B$ be a separation of $Y$ in $X$.
Then $\overline{A}\cap B=\emptyset=A\cap \overline{B}$.
Thus $\cl_{Y}(A)=\cl_{X}(A)\cap Y=\cl_{X}(A)\cap(A\cup B)=\cl_{X}(A)\cap A=A$
Similarly we have $\cl_{Y}(B)=B$.
It follows that $A,B$ are closed in $Y$.
Now since $A=Y\setminus B$ and $B=Y\setminus A$, we have both are open as well.