# Fixed point theorems
## Banach (Contraction mapping)
Let $(X,d)$ be a complete metric space.
Let $T:X\to X$ be a contraction.
Then $\exists!x_{0}\in X:T(x_{0})=x_{0}$.
### Perturbation of identity
Let $(X,\norm{\cdot})$ be a Banach space.
Let $x_{0},y_{0}\in X$ and $r>0$.
Let $\Phi:\overline{B_{r}(x_{0})}\to X$ s.t. $\Phi(x_{0})=y_{0}$.
Suppose $\exists$ contraction $\Psi:\overline{B_{r}(x_{0})}\to X$ s.t. $\Phi=\id+\Psi$.
Then denoting $\gamma=\lip(\Psi),R=(1-\gamma)r$, we have 
- $\forall y\in \overline{B_{R}(y_{0})}:\exists!x\in \overline{B_{r}(x_{0})}:\Phi(x)=y$

