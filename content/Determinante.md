---
title: Determinante
aliases:
  - determinantes
tags:
  - matemática
  - matrizes
---

# Determinante

Considere $Mn(\mathbb{R})$ o conjunto de [[Matriz|matrizes]] $n \times n$ com coeficientes reais. Para cada $n \geq 1$,

$$
\det :
\begin{gathered}
Mn(\mathbb{R}) \to \mathbb{R} \\
A \to \det A
\end{gathered}
$$

## Propriedades

1. Seja $A_i$ a linha $i$ da matriz $A$, então:

$$
\det(
\begin{bmatrix}
A_i \\
\cdot \cdot \cdot \\
\alpha X + \beta Y \\
\cdot \cdot \cdot \\
A_n
\end{bmatrix})
=
\alpha\det(
\begin{bmatrix}
A_i \\
\cdot \cdot \cdot \\
X \\
\cdot \cdot \cdot \\
A_n
\end{bmatrix})
+
\beta\det(
\begin{bmatrix}
A_i \\
\cdot \cdot \cdot \\
Y \\
\cdot \cdot \cdot \\
A_n
\end{bmatrix})
$$

2. A determinante de uma matriz pode ser calculada com desenvolvimento em cofatores a partir de qualquer linha ou coluna

3. Se $A$ possui 2 linhas iguais, $\det(A) = 0$.

4. Se $B$ é obtida multiplicando-se uma linha de $A$ por uma unidade escalar $\alpha$, então

$$
\det(B) = \alpha \det(A)
$$

$$
\text{Ex: } \det(
\begin{bmatrix}
1 & 4 \\
3 & 6
\end{bmatrix}
)
=
3 \det(
\begin{bmatrix}
1 & 4 \\
1 & 2
\end{bmatrix}
)
$$

5. Se $B$ é o resultado da troca de 2 linhas de A, então

$$
\det(B) = -\det(A)
$$

6. Se $B$ é obtida a partir da soma dela com outra linha multiplicada por um escalar, então

$$
\det(B) = \det(A)
$$

7. $\det(AB) = \det A \cdot \det B = det(BA)$

8. $\det(A^t) = 1/det A$

9. $\det(A^{-1}) = \det A$

## Métodos de Solução de Determinantes (SEPARAR EM NOTAS)

### Desenvolvimento em Cofatores

$Ã_{ij}$ é a menor do elemento $a_{ij}$. A menor é a submatriz $(n-1) \times (n-1)$ obtida eliminando-se a i-ésima linha e j-ésima coluna.

$ã_{ij}$ é o cofator de $a_{ij}$. Ele é definido por $ã_{ij} = (-1)^{i+j} \det (Ã_{ij})$.

Como o sinal da determinante altera dependendo da linha e coluna do cofator, é mais fácil visualizar com este exemplo com uma submatriz $3 \times 3$:

$$
\begin{bmatrix}
+ & - & + \\
- & + & - \\
+ & - & +
\end{bmatrix}
$$

Sendo $A$ uma matriz quadrada,

$$
\det(A) = a_{11}ã_{11} + a_{12}ã_{12} + \cdot \cdot \cdot + a_{1n}â_{1n}
$$

## Inversibilidade

A determinante de uma matriz permite definir se esta matriz possui ou não uma [[Matriz Inversa|matriz inversa]] definida.

1. $A$ é invertível $\iff$ $\det A \neq 0$

2. Se $AX = B$ tem única solução $\iff$ $A$ é invertível e $\det A \neq 0$

3. Se $AX = 0$ tem infinitas soluções $\iff$ $A$ é não-invertível e $\det A = 0$

$$
\begin{cases}
-2x + y = 0 \\
x - y + z = 0 \\
y - 2z = 0
\end{cases}
$$

$$
\left[
\begin{array}{ccc}
-2 & 1 & 0 \\
1 & -1 & 1 \\
0 & 1 & -2  \\
\end{array}
\right]
$$

$$
\left[
\begin{array}{ccc}
1 & 0 & -1 \\
0 & 1 & -2 \\
0 & 0 & 0  \\
\end{array}
\right]
$$

Como a [[Escalonamento|matriz escalonada]] possui uma linha nula, o sistema possui infinitas soluções e, portanto, $\det A = 0$.
