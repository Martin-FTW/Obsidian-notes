Book: [[Folland Real Analysis (RAMT&TA)]]
# Theorem 2.10 (Measurable functions can be approximated by simple functions from below)
Let $(X,\mathcal{M})$ be a measurable space.
Let $f:X\to \clcl{0}{\infty}$ be a measurable function.
Then $\exists$ simple functions $\phi_{n}:X\to \clcl{0}{\infty}$ s.t. 
1. $\forall j\in \mathbb{Z}_{>0}:0\leq \phi_{j}\leq \phi_{j+1}\leq f$
2. $\phi_{n}\to f$ pointwise
3. $\forall A\subseteq X$: if $f\vert_{A}$ is bounded then $\phi_{n}\vert_{A}\to f\vert_{A}$ uniformly 

Now let $g:X\to \mathbb{C}$ be a measurable function.
Then $\exists$ simple functions $\phi_{n}:X\to \mathbb{C}$ s.t. 
1. $\forall j\in \mathbb{Z}_{>0}:0\leq \abs{\phi_{j}}\leq \abs{\phi_{j+1}}\leq \abs{f}$
2. $\phi_{n}\to f$ pointwise
3. $\forall A\subseteq X$: if $f\vert_{A}$ is bounded then $\phi_{n}\vert_{A}\to f\vert_{A}$ uniformly 