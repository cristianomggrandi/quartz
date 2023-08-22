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
\left[
\begin{matrix}
1 & 3 \\
2 & -1
\end{matrix}  
\right]
\left[ 
\begin{matrix}
x \\
y
\end{matrix}  
\right]
=
\left[ 
\begin{matrix}
2 \\
0
\end{matrix}  
\right]
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