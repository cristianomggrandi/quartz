---
title: "Demonstração por Contraposição"
tags:
- matemática
- lógica
---
# Demonstração por Contraposição

Data: 04/08/2023

[[Demonstração por Contraposição]] é um tipo de [[Demonstração]] na qual podemos, ao invés de provar a [[Hipótese]] de que $P \Rightarrow Q$, podemos provar $\sim P \Rightarrow \; \sim Q$ (sua [[notes/Contrapositiva|Contrapositiva]]).

**Exemplo:** A proposição "Se $x^2$ é par, $x$ é par" tem como contrapositiva "Se $x$ é impar, $x^2$ é impar".

$$
\begin{equation}
\begin{gathered}
\text{Se x é impar, } x=2k + 1,\ k\in\mathbb{N} \\\\
x^2 = (2k + 1)^2 = 4k^2 + 4k + 1 = 2(2k^2 + 2k) + 1 \\\\
\text{Se assumimos que } q = 2k^2 + 2k \text{, então } x^2 = 2q + 1 \\\\
\text{Como sabemos que }k\text{ é par, } q \text{ é par.} \\\\
\text{Portanto, } x^2 \text{ é ímpar }. \ \blacksquare
\end{gathered}
\end{equation}
$$