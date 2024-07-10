Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Theorem I.2.7 (Canonical decomposition of a function)
Let $f:A\to B$ be a function.
Define $\sim$ by $a'\sim a''\iff f(a')=f(a'')$ for any $a',a''\in A$.
Then $f$ decomposes as follows: 
```tikz
\usepackage{tikz-cd}
\usepackage{amsmath}
\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZABgBpiBdUkANwEMAbAVxiRAEEQBfU9TXfIRQBGclVqMWbdgHpgAHXnYAtl268QGbHgJEATGOr1mrRCEUQ0MAE50cEa2DrKYwLKoAEAM3V9tgogBmQwkTNgAhbnEYKABzeCJQL2sIZSQyEHskURAACxg6KDYcAHcIfMKEHiSUtMQcrMQDUKkzRRUQagY6ACMYBgAFfh0hEAYYLxxfEGTU7OpG5uNW83keumtgLzUu3v6h-10zayxY3KnqmdqkZsbgzLosBjZciAgAa2nZuoy76j6wEVEIEMnBclhJukjJJTDMolwgA
\begin{tikzcd}
A \arrow[r, two heads] \arrow[rrr, "f", bend left] & A/{\sim} \arrow[r, "\sim"] \arrow[r, "\bar{f}"'] & \operatorname{im} f \arrow[r, hook] & B
\end{tikzcd}
\end{document}
```
where the first function is the canonical projection, third function is the inclusion $\im f\subseteq B$, and $\bar{f}$ is a bijection defined by $\bar{f}([a]_{\sim})=f(a)$for all $a\in A$.
#### Proof
easy