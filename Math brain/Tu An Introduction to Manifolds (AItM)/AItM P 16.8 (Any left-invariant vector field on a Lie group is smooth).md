Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 16.8 (Any left-invariant vector field on a Lie group is smooth)
Let $X$ be a left-invariant vector field on a Lie group $G$.
Then $X$ is smooth.
#### Proof
Let $f\in C^{\infty}(G)$. 
Choose a smooth curve $c:I \to G$ with $c(0)=e,c'(0)=X_{e}$.
Then for $g\in G$, we have $gc(0)=ge=e$ and $(gc)'(0)=(\ell_{g}\circ c)'(0)=\ell_{g}\pushforward c'(0)=\ell_{g}\pushforward X_{e}=X_{ge}=X_{g}$.
Hence $\displaystyle (Xf)(g)=X_{g}f=\left.\frac{d}{dt}\right\vert_{0}f(gc(t))$ by [[AItM P 8.17 (Tangent vector as a directional derivative)]].
Note that $f(gc(t))$ is a composition of smooth functions: 
$$
\begin{array}{cccccccc}
G\times I&{}\xrightarrow{\id_{G}\times c}&G\times G&\xrightarrow \mu {}&G&\xrightarrow{f}{} &\mathbb{R}\\
(g,t)&\xmapsto{\hspace{25pt}}&(g,c(t))&\xmapsto{}{}&gc(t)&\mapsto{}&f(gc(t))

\end{array}$$, thus is smooth.
Now $\displaystyle F(g,t)\coloneqq\frac{d}{dt}f(gc(t))$ is smooth as well.
Note that $(Xf)(g)$ is a composition of smooth functions:
$$\begin{array}{cccl}
G&\to&G\times I&\xrightarrow F&\mathbb{R} \\
g&\mapsto&(g,0)&\mapsto&F(g,0)=\left.\dfrac{d}{dt}\right\vert_{0}f(gc(t))
\end{array}$$
, thus is smooth on $G$.
Hence $X$ is a smooth vector field by [[AItM P 14.3 (Smoothness of a vector field in terms of functions)]].

