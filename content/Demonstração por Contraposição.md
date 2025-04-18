---
title: Demonstração por Contraposição
aliases:
  - demonstrações por contraposição
  - prova por contraposição
  - provas por contraposição
tags:
  - matemática
  - lógica
---

# Demonstração por Contraposição

Data: 04/08/2023

Demonstração por contraposição é um tipo de [[Demonstração|demonstração]] na qual podemos, ao invés de provar a hipótese de que $P \Rightarrow Q$, podemos provar $\sim Q \Rightarrow \sim P$ (sua [[Contrapositiva|contrapositiva]]).

Para provar $\forall x \in D: P(x) \implies Q(x)$, podemos provar sua contrapositiva: $\forall x \in D: \lnot Q(x) \implies \lnot P(x)$

**Exemplo:** A [[Proposição|proposição]] "Se $x^2$ é par, $x$ é par" tem como [[Contrapositiva|contrapositiva]] "Se $x$ é impar, $x^2$ é impar".

$$
\begin{gathered}
\text{Se x é impar, } x=2k + 1,\ k\in\mathbb{N} \\\\
x^2 = (2k + 1)^2 = 4k^2 + 4k + 1 = 2(2k^2 + 2k) + 1 \\\\
\text{Se assumimos que } q = 2k^2 + 2k \text{, então } x^2 = 2q + 1 \\\\
\text{Como sabemos que }k\text{ é par, } q \text{ é par.} \\\\
\text{Logo, } x^2 \text{ é ímpar }. \blacksquare
\end{gathered}
$$
