Book: [[Aluffi Algebra Chapter 0 (AC0)]]
# Example I.2.4 (Natural projections of product)
Let $A,B$ be sets.
Then there are natural projections $\pi_{A},\pi_{B}:$
```tikz
\usepackage{tikz-cd}\begin{document}
% https://tikzcd.yichuanshen.de/#N4Igdg9gJgpgziAXAbVABwnAlgFyxMJZARgBoAGAXVJADcBDAGwFcYkQBBAHS7wFt4AAgBCIAL6l0mXPkIpypYtTpNW7DuMkgM2PASIAmRcoYs2iEKLHKYUAObwioAGYAnCHyQKQOCEjIqZuw8aFgA+ho0jPQARjCMAArSenIgrlh2ABY4IDSZMPRQ7DgA7hD5hQgSLu6eiN6+SEaBahYh4aJ5BUUWpeXdVZRiQA
\begin{tikzcd} & A\times B \arrow[ld, "\pi_A"', two heads] \arrow[rd, "\pi_B", two heads] & \\
A & & B
\end{tikzcd}
\end{document}
```
defined by $\pi_{A}(a,b)=a,\pi_{B}(a,b)=b$ for all $(a,b)\in A\times B$.
Both $\pi_{A},\pi_{B}$ are surjective.