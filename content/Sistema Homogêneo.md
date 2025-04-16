---
title: "Sistema Homogêneo"
aliases:
- sistemas homogêneos
- sh
tags:
- matemática
---
# Sistema Homogêneo

Um [[notes/Sistema de Equações Lineares|sistema de equações lineares]] $AX = B$, em que $B = 0$ é chamado de Sistema Homogêneo.

**Exemplo:**


$$
\begin{cases}
\begin{gather*}
x + y = 0 \\
x - y = 0
\end{gather*}
\end{cases}
$$

Sua [[notes/Escalonamento|forma escalonada]] se dá por:

$$
\left[
\begin{array}{cc|c}
1 & 0 & 0 \\
0 & 1 & 0
\end{array}
\right]
$$

A solução $(0, \cdot \cdot \cdot, 0)$ sempre é solução de um SH.

Um SH pode ter uma única solução ou infinitas soluções.

## Teorema

O [[notes/Teorema|teorema]] dos sistemas homogêneos diz que:

Se, em um SEL $A_{m \times n}$, $m < n$ (mais variáveis que equações), então o SH $AX = 0$ tem infinitas soluções.

## Propriedades

Seja $AX = 0$, $A_{m \times n}$. Então:

1. Se $X_1$ e $X_2$ são soluções de $AX = 0$, $X_1 + X_2$ também é solução.

$$A(X_1 + X_2) = AX_1 + AX_2 = 0 + 0 = 0$$

1. Se $X_1$ é solução, $\alpha X_1$ também é solução.

$$A(\alpha X_1) = \alpha(AX_1) = \alpha 0 = 0$$