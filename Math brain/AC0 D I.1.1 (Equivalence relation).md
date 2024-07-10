Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Definition I.1.1 (Equivalence relation)
Let $S$ be a set and $\sim$ be a relation on $S$.
We call $\sim$ an equivalence relation if $\sim$ satisfies:
1. Reflexivity: $\forall a\in S:a\sim a$
2. Symmetry: $\forall a,b\in S:a\sim b\implies b\sim a$
3. Transitivity: $\forall a,b,c\in S:(a\sim b\land b\sim c)\implies a\sim c$.

In this case, we define the following:
1. $\forall a\in S$, $[a]_{\sim}=\set{b\in S\given b\sim a}$ is called the equivalence class of $a$ w.r.t. $\sim$.
2. $\mathscr{P}_{\sim}=\set{[a]_{\sim}\given a\in S}$  is called the induced partition of $S$ from $\sim$.
