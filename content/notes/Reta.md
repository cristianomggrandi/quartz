---
title: Retas
aliases:
  - retas
tags:
  - álgebra-linear
  - matemática
  - geometria
---
# Reta

Equação reduzida da reta em $\mathbb{R}^2: ax + b, a = \tan \alpha$.

Equação **vetorial** da reta $r$: $P + t \vec{PQ}, t \in \mathbb{R}$. $\vec{PR}$ é o [[notes/Vetor|vetor]] diretor da reta $r$.

A equação **paramétrica** de $r$ é obtida colocando $x$ e $y$ em termos de $t$.

A equação **simétrica** de $r$ é obtida isolando $t$ e igualando as duas expressões.

**Exemplo:** $r$ tem origem em $(1, -3)$ e o vetor diretor é o $(1, 5)$.

$$r = (1, -3) + t(1, 5)$$
$$r = (1 + t, -3 + 5t)$$

$$
\text{Equação paramétrica: } 
\begin{cases}
\begin{gather*}
x = 1 + t \\
y = -3 + 5t
\end{gather*}
\end{cases}
$$

$$
\text{Equação simétrica: }
\begin{cases}
\begin{gather*}
t = x - 1 \\
t = \frac{y + 3}{5}
\end{gather*}
\end{cases}
\implies
x - 1 = \frac{y + 3}{5}
$$

## Posição Relativa

Em relação ao vetor diretor:

- Há intersecção?
	- Sim
		- São paralelos?
			- Sim: **Coincidentes**
			- Não: **Concorrentes**
	- Não
		- São paralelos?
			- Sim: **Paralelos**
			- Não: **Reversos**

Retas reversas estão em planos diferentes, mas paralelos entre si.