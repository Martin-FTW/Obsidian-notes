Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 16.13 (Pushforward of left-invariant vector field by a Lie group homomorphism is related to the original vector field)
Let $F:H\to G$ be a Lie group homomorphism.
Let $X$ be a left-invariant vector field on $H$.
Then $F\pushforward X$ is $F$-related to $X$.
#### Proof
Let $h\in H$.
Then
$F\pushforward X(F(h))$
$=(F\pushforward[,e](X_{e}))\tilde{\ }(F(h))$ by definition of $F\pushforward X$
$=\ell_{F(h)}\pushforward[,e](F\pushforward[,e](X_{e}))$ by definition of  $\tilde{}$
$=(\ell_{F(h)}\circ F)\pushforward[,e](X_{e})$ by chain rule
$= (F\circ \ell_{h})\pushforward[,e](X_{e})$ by $F$ is Lie group homo
$=(F\pushforward[,h]\circ \ell_{h}\pushforward[,e])(X_{e})$ by chain rule
$=F\pushforward[,h](X_{h})$ by $X$ is left-invariant
