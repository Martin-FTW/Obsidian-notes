Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 16.14 (Differential of Lie group homomorphism is a Lie algebra homomorphism)
Let $F:H\to G$ be a Lie group homomorphism.
Then $F\pushforward[,e]:T_{e}H\to T_{e}G$ is a Lie algebra homomorphism.
That is, a linear map s.t. $F\pushforward[,e]\lie{A}{B}=\lie{F\pushforward[,e]A}{F\pushforward[,e]B}$.
#### Proof
Let $A,B\in T_{e}H$.
$F\pushforward[,e]\lie{A}{B}$
$=F\pushforward[,e]\lie{\tilde{A}}{\tilde{B}}_{e}$ by definition [[AItM Ep (Isomorphism between tangent space at identity and the subalgebra of left-invariant vector fields)]]
$=\lie{F\pushforward \tilde{A}}{F\pushforward\tilde{B}}_{F(e)}$ by [[AItM P 16.13 (Pushforward of left-invariant vector field by a Lie group homomorphism is related to the original vector field)]]
$=\lie{F\pushforward\tilde{A}}{F\pushforward\tilde{B}}_{e}$ by $F$ homo
$=\lie{(F\pushforward[,e]A)\tilde{\ }}{(F\pushforward[,e]B)\tilde{\ }}_{e}$ by definition [[AItM D 16.12 (Pushforward of a left-invariant vector field by a Lie group homomorphism)]]
$=\lie{F\pushforward[,e] A}{F\pushforward[,e] B}$ by definition [[AItM D (Lie bracket on tangent space at identity)]]