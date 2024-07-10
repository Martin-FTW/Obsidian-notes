Book: [[MATH3030]]
# Proposition (Normal subgroups of direct product)
Let $G_{1},\dots,G_{n}$ be groups and $N_{i}\unlhd G_{i}$ for all $i$.
Then $\prod N_{i}\unlhd \prod G_{i}$ and $\prod G_{i}/\prod N_{i}\cong \prod(G_{i}/N_{i})$.
#### Proof
Let $a=(a_{1},\dots,a_{n})\in \prod G_{i},h=(h_{1},\dots,h_{n})\in \prod N_{i}$.
Since $N_{i}$ are normal, we have $a_{i}h_{i}a_{i}^{-1}\in N_{i}$.
Then $aha^{-1}=(a_{1}h_{1}a_{1}^{-1},\dots,a_{n}h_{n}a_{n}^{-1})\in \prod N_{i}$.
It follows that $\prod N_{i}$ is normal.
Now let $\varphi:\prod G_{i}\to \prod(G_{i}/N_{i})$ be $\varphi(g_{1},\dots,g_{n})=(g_{1} N_{1},\dots,g_{n}N_{n})$.
Then $\ker \varphi=\prod N_{i}$.