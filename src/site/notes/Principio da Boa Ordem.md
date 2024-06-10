---
{"dg-publish":true,"permalink":"/principio-da-boa-ordem/","tags":["gardenEntry"]}
---

---
Princípio da Boa Ordem: todo subconjunto não vazio de $\mathbb N$ ([[Conjunto dos Números Naturais\|Conjunto dos Números Naturais]]) possui um menor elemento.

Demonstração:

Seja $S$ um tal subconjunto de $\mathbb N$ e consideremos o conjunto $M=${$n\in \mathbb N | n\leq x$, para todo $x\in S$}. Claro que $0\in M$. Como $S\neq \emptyset$, tome $s\in S$. Então $s+1\notin M$, pois $s+1$ não é menor ou igual a $s$. Assim, $M\neq \mathbb N$. Como $0\in M$ e $M\neq \mathbb N$, deve existir $m\in M$ tal que $m+1\notin M$, caso contrário, pelo Princípio de Indução, $M$ deveria ser $\mathbb N$.

Afirmamos que um tal $m$ é o menor elemento de $S$, isto é, $m=minS$.

Como $m\in M$, então $m\leq x$, $\forall x\in S$.

Pelo teorema anterior, teríamos $m+1\leq x$, $\forall x\in S$, do que resultaria $m+1\in M$, em contradição com a escolha de $m$.

Logo $m\in S$, conforme queríamos.
