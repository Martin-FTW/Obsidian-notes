Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Proposition I.2.1 (left-inverse iff inj, right-inverse iff surj)
Let $A\neq \emptyset$ and $f:A\to B$ be a function.
Then
1. $f$ has left-inverse ($\exists g:B\to A$ s.t. $g\circ f=\id_{A}$) iff $f$ is injective
2. $f$ has right-inverse ($\exists g:B\to A$ s.t. $f\circ g=\id_{B}$) iff $f$ is surjective 

#### Proof
$1.(\implies)$
Let $x,y\in A$ s.t. $f(x)=f(y)$.
Then $x=g\circ f(x)=g(f(x))=g(f(y))=g\circ f(y)=y$.
Hence $f$ is injective
$1.(\impliedby)$
Since $A\neq \emptyset$, $\exists s\in A$.
Now define a function $g:B\to A$ by $g(b)=\begin{cases}a&\text{if }\exists a\in A:b=f(a)\\s&\text{if }b\notin \im f\end{cases}$ for any $b\in B$.
Then $g\circ f=\id_{A}$. 

For $2.$ see [[AC0 Ex I.2.2]]