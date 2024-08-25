Book: [[Munkres Topology (MT)]]
# Theorem 17.2 (Closed in subspace)
Let $Y$ be a subspace of $X$ and $A\subset Y$.
Then $A$ is closed in $Y$ iff $A=C\cap Y$ for some closed set $C$ of $X$.
#### Proof
$(\implies):$ Suppose $A$ is closed in $Y$, i.e. $Y\setminus A$ is open in $Y$.
Thus $\exists U$ open in $X$ s.t. $Y\setminus A=U\cap Y$. Thus $X\setminus U$ is closed in $X$.
Then $A=Y\setminus (Y\setminus A)=Y\setminus (U\cap Y)=(X\cap Y)\setminus(U\cap Y)=(X\setminus U)\cap Y$.
$(\impliedby):$ Suppose $A=C\cap Y$ for some closed set $C$ of $X$.
Then $X \setminus C$ is open in $X$.
Hence $Y\setminus A=Y\setminus(C\cap Y)=(X\cap Y)\setminus(C\cap Y)=(X\setminus C)\cap Y$ is open in $Y$.
It follows that $A$ is closed in $Y$.