---
title: Demonstração Direta
aliases:
  - demonstrações diretas
  - prova direta
  - provas diretas
tags:
  - matemática
  - lógica
---

# Demonstração Direta

Data: 04/08/2023

Demonstração direta é um tipo de [[Demonstração|demonstração]] na qual, partindo da hipótese e por meio da argumentação, chegamos à tese.

Supondo que $\forall x \in D: P(x) \implies Q(x)$, prove que $Q(x)$ se $P(x)$.

**Exemplo:** Seja $x$ um inteiro. Se $x$ é par, então $x^2$ é par.

$$
\begin{gathered}
\text{Se x é par, } x=2k,\ k\in\mathbb{N} \\\\
x^2 = (2k)^2 = 4k^2 = 2(2k^2) \\\\
\text{Se assumimos que } q = 2k^2 \text{, então } x^2 = 2q \\\\
\text{Como sabemos que }k\text{ é par, } q \text{ é par.} \\\\
\text{Logo, } x^2 \text{ é par }. \blacksquare
\end{gathered}
$$
