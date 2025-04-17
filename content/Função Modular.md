---
title: Função Modular
aliases:
  - funções modulares
tags:
  - matemática
---

# Função Modular

Uma [[Função|função]] modular é uma função na qual, dado o nímero real $x$, definimos o valor absoluto de $x$, ou módulo de x, como:

$$
\vert x \vert =
\begin{cases}
\begin{gather*}
x \text{ se } x \geq 0 \\
-x \text{ se } x < 0
\end{gather*}
\end{cases}
$$

## Equação Modular

Se $\vert a \vert$ = b, então $b \geq 0$ e $b = a$ ou $b = -a$.

**Exemplo:**

$$\vert 2x - 5 \vert - \vert x - 2 \vert = 3x + 1$$

|                                          |  $x < 2$  | $2 \leq x < \frac{5}{2}$ | $x \geq \frac{5}{2}$ |
| :--------------------------------------: | :-------: | :----------------------: | :------------------: |
|             $\vert2x-5\vert$             | $-2x + 5$ |        $-2x + 5$         |       $2x - 5$       |
|           $\vert x - 2 \vert$            | $-x + 2$  |         $x - 2$          |       $x - 2$        |
| $\vert 2x - 5 \vert - \vert x - 2 \vert$ | $-x + 3$  |        $-3x + 7$         |       $x - 3$        |

- Se $x < 2$, $-x + 3 = 3x + 1$. Logo, $x = \frac{1}{2}$.
- Se $2 \leq x < \frac{5}{2}$, $-3x + 7 = 3x + 1$. Logo, $x = 1$.
- Se $x \geq \frac{5}{2}$, $x - 3 = 3x + 1$. Logo, $x = -2$.

Como $1 \notin [2, \frac{5}{2})$ e $-2 \notin [-\frac{5}{2}, \infty)$, então

$$x = \frac{1}{2}$$

## Inequação Modular

$\vert A \vert \leq C \iff A \in [-C, C]$

$\vert A \vert \geq C \iff A \in (-\infty, -C] \cup [C, \infty)$

**Exemplo:**

$$\vert 4x^2 - 1 \vert \leq x + 2$$

$-x - 2 \leq 4x^2 - 1 \leq x + 2$

$4x^2 - 1 \geq -x - 2 \iff 4x^2 + x + 1 \geq 0$.

Como não há raízes e $x$ é sempre maior que 0, $S = \mathbb{R}$.

$4x^2 - 1 \leq x + 2 \iff 4x^2 - x - 3 \geq 0$. As raízes são $1$ e $-\frac{3}{4}$. Como $a > 0$, $S = [-\frac{3}{4}, 1]$.

A solução será a intercessão dos conjuntos.

$$S = \mathbb{R} \cap \left[ -\frac{3}{4}, 1 \right] = \left[ -\frac{3}{4}, 1 \right]$$

**Exemplo 2:**

|                                          | $x < \frac{2}{5}$ | $\frac{2}{5} \leq x < 3$ | $x \geq 3$ |
| :--------------------------------------: | :---------------: | :----------------------: | :--------: |
|           $\vert x - 3 \vert$            |     $-x + 3$      |        $-2x + 5$         |  $2x - 5$  |
|           $\vert x - 2 \vert$            |     $-x + 2$      |         $x - 2$          |  $x - 2$   |
| $\vert 2x - 5 \vert - \vert x - 2 \vert$ |     $-x + 3$      |        $-3x + 7$         |  $x - 3$   |

Se $x < \frac{2}{5}$, $4x + 1 \geq x - 2 \iff x \geq -1$. Então $x \in \left[ -1, \frac{2}{5} \right]$.

Se $\frac{2}{5} \leq x < 3$, $-6x + 5 \geq x - 2 \iff x \leq 1$. Então $x \in \left[ \frac{2}{5}, 1 \right]$.

Se $x > 3$, $-4x - 1 \geq x - 2 \iff x \leq \frac{1}{5}$. Então $\varnothing$.

A solução será a união dos conjuntos.

$$S = \varnothing \cup \left[ -1, \frac{2}{5} \right] \cup \left[ \frac{2}{5}, 1 \right] = \left[ -1, 1 \right]$$
