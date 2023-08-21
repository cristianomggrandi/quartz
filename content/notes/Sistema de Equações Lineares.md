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
\begin{bmatrix}
1 & 3 \\
2& -1
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
=
\begin{bmatrix}
2 \\
0
\end{bmatrix}
$$

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

Um conjunto solução para um SEL é um conjunto de todas as soluções possíveis para este SEL.

Para solucionar um SEL, é possível utilizar a técnica do [[notes/Escalonamento|escalonamento]].