Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 14.17 (Lie bracket of related vector fields is related)
Let $N,M$ be manifolds and $F:N\to M$ be smooth.
Let $X,Y$ be vector fields on $N$ and $\bar{X},\bar{Y}$ be vector fields on $M$.
Suppose $X,Y$ are $F$-related to $\bar{X},\bar{Y}$ respectively.
Then $\lie{X}{Y}$ is $F$-related to $\lie{\bar{X}}{\bar{Y}}$.
#### Proof
Let $g\in C^{\infty}(M)$.
Then $$\begin{align}
\lie{X}{Y}(g\circ F)&=(XY-YX)(g\circ F) \\
&=XY(g\circ F)-YX(g\circ F) \\
&=X(\bar{Y}g\circ F)-Y(\bar{X}g\circ F) \\
&=\bar{X}\bar{Y}g\circ F-\bar{Y}\bar{X}g\circ F \\
&=((\bar{X}\bar{Y}-\bar{Y}\bar{X})g)\circ F \\
&=(\lie{\bar{X}}{\bar{Y}}g)\circ F 
\end{align}$$
Thus $[\bar{X},\bar{Y}]$ is $F$-related to $\lie{X}{Y}$ by [[AItM P 14.16 (Characterization of related vector fields)]]
