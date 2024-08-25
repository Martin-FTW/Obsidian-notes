Book: [[Munkres Topology (MT)]]
# Definition (Closure, interior)
Let $(X,\mathscr{T})$ be a topological space and $A\subset X$.
- The union of all open sets contained in $A$ is called the interior of $A$ and denoted as  $\interior A\coloneqq\displaystyle \bigcup_{\substack{U\in \mathscr{T}\\U\subset A}}U$.
- The intersection of all closed sets containing $A$ is called the closure of $A$ and is denoted as $\displaystyle \bar{A}=\cl_{X} A=\bigcap_{\substack{X\setminus C\in \mathscr{T}\\A\subset C}}C$.

Note that
- $\interior A\subset A\subset \bar{A}$
- If $A$ is open then $A=\interior A$
- If $A$ is closed then $A=\bar{A}$