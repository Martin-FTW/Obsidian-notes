Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Proposition I.2.3 (Injective iff set mono)
Let $f:A\to B$ be a function.
Then $f$ is injective iff $f$ is a set monomorphism, 
	i.e. $\forall$ set $Z$ and $\forall \alpha',\alpha'':Z\to A$, $f\circ \alpha'=f\circ \alpha''\implies \alpha'=\alpha''$.

#### Proof
$(\implies):$
Since $f$ is injective, it has a left inverse $g:B\to A$.
Let $Z$ be any set and $\alpha',\alpha'':Z\to A$ be functions s.t. $f\circ \alpha'=f\circ \alpha''$.
Then $\alpha'=g\circ f\circ \alpha'=g\circ f\circ \alpha''=\alpha''$.
Hence $f$ is a set mono.
$(\impliedby):$
Let $a',a''\in A$ s.t. $f(a')=f(a'')$.
Since $A\neq \emptyset$, $\exists p\in A$.
Let $Z=\set{p}$ and $\alpha',\alpha'':Z\to A$ be $\alpha'(p)=a',\alpha''(p)=a''$.
Now $f\circ \alpha'(p)=f(a')=f(a'')=f\circ \alpha''(p)$, hence $f\circ \alpha'=f\circ \alpha''$.
Since $f$ is monic, we have $\alpha'=\alpha''$.
Thus $a'=\alpha'(p)=\alpha''(p)=a''$.
Hence $f$ is injective.