---
title: "Sistema de Equações Lineares"
aliases:
- sistemas de equações lineares
- sel
tags:
- matemática
---
# Sistema de Equações Lineares

Um sistema de equações lineares (SEL) é um conjunto de [[notes/Equação Linear|equações lineares]].

**Exemplo:**

$$
\begin{cases}
x + 3y = 2\\
2x - y = 0
\end{cases}
$$

## Representação Matricial

A representação [[notes/Matriz|matricial]] de um SEL é dada pelo produto dos coeficientes que acompanham as variáveis por uma [[notes/Matriz Coluna|matriz coluna]] com as variáveis igualada a uma matriz com o resultado.

**Exemplo:**

$$
AX = B
$$
$$
A =
\begin{bmatrix}
1 & 3 \\
2 & -1
\end{bmatrix}
$$
$$
X =
\begin{bmatrix}
x \\
y
\end{bmatrix}
$$
$$
B =
\begin{bmatrix}
2 \\
0
\end{bmatrix}
$$

*Obs.: A renderização de mais de uma matriz na mesma linha não funciona, por isso separei em linhas diferentes.*

A matriz aumentada do SEL definido por $AX = B$ é definida por $[A|B]$

$$
[A|B] = 
\left[
\begin{array}{cc|c}
1 & 3 & 2 \\
2 & 1 & 0
\end{array}
\right]
$$

## Conjunto Solução

Um conjunto solução ($S$) para um SEL é um conjunto de todas as soluções possíveis para este SEL.

Para solucionar um SEL, é possível utilizar a técnica do [[notes/Escalonamento|escalonamento]].

## Tipos de SEL

Um SEL pode ser de 3 tipos, dependendo do número de soluções que ele possui:

- Impossível (0 soluções)

O SEL é impossível se sua [[notes/Escalonamento|matriz escalonada]] possuir uma linha na forma

$$[0  \cdot \cdot \cdot 0 | K], K \neq 0$$

**Exemplo:**

$$
\left[
\begin{array}{ccc|c}
1 & 0 & -2 & 3 \\
0 & 1 & 5 & 2 \\
0 & 0 & 0 & \fbox{-4} \\
\end{array}
\right]
$$

- Possível e indeterminado (infinitas soluções)

O SEL é possível e indeterminado se sua [[notes/Escalonamento|matriz escalonada]] possuir menos linhas nulas 

**Exemplo:**

$$
\left[
\begin{array}{cccc|c}
1 & 3 & 0 & 2 & -5 \\
0 & 0 & 1 & -3 & 2 \\
0 & 0 & 0 & 0 & 0 \\
\end{array}
\right]
$$

Sendo $\alpha = y$ e $\beta = w$, $\alpha, \beta \in \mathbb{R}$, temos que:

$$
\begin{cases}
x = -5 -3\alpha - 2\beta \\
z = 2 + \beta
\end{cases}
$$

$$
S =
\begin{cases}
\begin{gather*}
-5 -3\alpha - 2\beta \\
\alpha \\
2 + \beta \\
\beta
\end{gather*}
\end{cases}
$$

- Possível e determinado (1 solução)

## Sistemas Específicos

- [[notes/Sistema Homogêneo|Sistema Homogêneo]]