Book: [[Tu An Introduction to Manifolds (AItM)]]
# Proposition 15.11 (Embedded Lie subgroup)
Let $G$ be a Lie group.
Let $H$ be a subgroup and a regular submanifold of $G$.
Then $H$ is a Lie subgroup of $G$.
We call such $H$ an embedded Lie subgroup of $G$.
#### Proof
Since $H$ is a regular submanifold, it is the image of an embedding by [[AItM T 11.14 (A regular submanifold is an embedded submanifold by inclusion)]].
Hence $H$ is an immersed submanifold of $G$.
Thus the inclusion $i:H\to G$ is smooth.
Hence $i\times i:H\times h\to G\times G$ is smooth as well.
Denote the multiplcation map in $G$ by $\mu$.
Now $\mu \circ(i\times i):H\times H\to G$ is smooth.
Hence restricting the codomain to $\mu \circ(i\times i):H\times H\to H$ is still smooth by [[AItM T 11.15 (Restricting the codomain of a smooth map to a regular submanifold preserve smoothness)]].
Folowing [[AItM Eg 15.5 (Special linear group is a Lie group)]], we have the inverse map is smooth.