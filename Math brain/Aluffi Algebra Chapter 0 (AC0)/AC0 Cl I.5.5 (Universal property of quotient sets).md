Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Claim I.5.5 (Universal property of quotient sets)
Let $A$ be a set and $\sim$ be an equivalence relation on $A$.
Let $\pi$ be the canonical projection in [[AC0 Eg I.2.6 (Canonical projection of quotient)]]. 
Then the quotient $A/{\sim}$ is universal w.r.t. the property of mapping $A$ to a set in such a way that equivalent elements have the same image"
Translating the statement, we have
- $\forall Z\in \obj(\mathsf{Set}), \varphi:A\to Z,\exists!\bar{\varphi}:A/{\sim} \to Z$ s.t. $\varphi=\bar{\varphi}\circ \pi$ 

Or in categorical terms, we have
- $(\pi,A/\sim)$ is an initial object in the category where
	- Objects are $(\varphi,Z)$, where $Z$ is a set and $\varphi:A\to Z$ is a function satisfying $a'\sim a''\implies \varphi(a')=\varphi(a'')$
	- Morphisms $(\varphi_{1},Z_{1})\to(\varphi_{2},Z_{2})$ are commutative diagrams induced by the function $\sigma:Z_{1}\to Z_{2}$.