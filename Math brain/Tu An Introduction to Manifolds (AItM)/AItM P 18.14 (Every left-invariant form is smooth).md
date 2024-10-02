Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 18.14 (Every left-invariant form is smooth)
Let $G$ be a Lie group.
Let $\omega$ be a left-invariant $k$-form on $G$.
Then $\omega$ is smooth.
#### Proof
Let $X_{1},\dots,X_{k}$ be smooth vector fields on $G$.
Let $(Y_{1})_{e},\dots,(Y_{n})_{e}$ be a basis for $T_{e}G$ and $Y_{1},\dots,,Y_{n}$ the left-invariant vector fields they generate respectively.
Thus $Y_{1},\dots,Y_{n}$ is a smooth frame on $G$ by [[AItM P 16.8 (Any left-invariant vector field on a Lie group is smooth)]].
Now each $X_{j}$ can be written as $X_{j}=\sum a_{j}^{i}Y_{i}$, where the functions $a_{j}^{i}\in C^{\infty}(G)$ by [[AItM P 12.12 (Characterization of smooth sections)]].
Since
$(\omega(Y_{i_{1}},\dots,Y_{i_{k}}))(g)=\omega_{g}((Y_{i_{1}})_{g},\dots,(Y_{i_{k}})_{g})$
$=(\ell_{g^{-1}}\pullback(\omega_{e}))(\ell_{g}\pushforward(Y_{i_{1}})_{e},\dots ,\ell_{g}\pushforward(Y_{i_{k}})_{e})$
$=\omega_{e}((Y_{i_{1}})_{e},\dots,(Y_{i_{k}})_{e})$
is a constant function independent of $g$, we have $\omega(Y_{i_{1}},\dots,Y_{i_{k}})$ is smooth on $G$.
Hence $\omega(X_{1},\dots,X_{k})$ is smooth on $G$.
Thus $\omega$ is smooth by [[AItM P 18.7 (Characterization of a smooth k-form)]]