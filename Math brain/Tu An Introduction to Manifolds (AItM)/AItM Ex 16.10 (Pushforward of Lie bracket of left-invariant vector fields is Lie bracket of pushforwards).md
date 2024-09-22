Book: [[Tu An Introduction to Manifolds (AItM)]]
# Exercise 16.10 (Pushforward of Lie bracket of left-invariant vector fields is Lie bracket of pushforwards)
Let $F:H\to G$ be a Lie group homomorphism.
Let $X,Y\in L(H)$.
Then $F\pushforward\lie{X}{Y}=\lie{F\pushforward X}{F\pushforward Y}$.
#### Proof
$F\pushforward\lie{X}{Y}$
$=(F\pushforward[,e]\lie{X}{Y}_{e}) \tilde{\ }$
$=(F\pushforward[,e]\lie{X_{e}}{Y_{e}})\tilde{\ }$
$=(\lie{F\pushforward[,e]X_{e}}{F\pushforward[,e]Y_{e}})\tilde{\ }$
$=(\lie{(F\pushforward X)_{e}}{(F\pushforward Y)_{e}})\tilde{\ }$
$=(\lie{F\pushforward X}{F\pushforward Y}_{e})\tilde{\ }$
$=\lie{F\pushforward X}{F\pushforward Y}_{e}$