Book: [[doCarmo Differential Geometry of Curves & Surfaces (DGoC&S)]]
# Proposition 2.6.2 (Level surfaces are orientable)
Let $U\subseteq \mathbb{R}^{3}$ be open. 
Let $f:U\to \mathbb{R}$ be differentiable and $a\in \mathbb{R}$ be a regular value of $f$.
Then $S=f^{-1}(\set{a})$ is orientable.
#### Proof
Let $p=(x_{0},y_{0},z_{0})\in S$
Let $\alpha:I\to S$ be a parametrized curve passingthrough $p$ at $t_{0}\in I$.
Then $f\circ \alpha \equiv 1$, thus $f_{x}(p)\alpha_{1}'(t_{0})+f_{y}(p)\alpha_{2}'(t_{0})+f_{z}(p)\alpha_{3}'(t_{0})=0$ by chain rule.
That is, $\innerp{\nabla f(p)}{\alpha'(t_{0})}{}=0$.
Now $N=\dfrac{\nabla f}{\norm{\nabla f}}$ is a continuous unit normal vector field.