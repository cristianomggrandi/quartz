---
title: Matriz Inversa
aliases:
  - matrizes inversas
  - invertível
tags:
  - matemática
---

# Matriz Inversa

Se a [[Matriz|matriz]] $A$ tem matriz inversa $B$,

$$A \cdot B = B \cdot A = I$$

**Exemplo:**

$$
A =
\begin{bmatrix}
1 & 2 \\
0 & 1
\end{bmatrix}
$$

$$
B =
\begin{bmatrix}
1 & -2 \\
0 & 1
\end{bmatrix}
$$

$$
A \cdot B = I =
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}
$$

## Prova

Para provar que $B$ é inversa de $A$ e vice-versa, devemos provar tanto $AB = I$ quanto $BA = I$.

## Propriedades

- A matriz inversa é única.

  > Se $B$ e $C$ são matrizes inversas de $A$, temos que $AB = BA = I$ e $AC = CA = I$.
  > $B = BI = B \cdot (AC) = (BA)C = IC = C$

- Se $A$ é invertível, $\exists A^{-1}$ tal que $(A^{-1})^{-1} = A$.

  > Como $A \cdot A^{-1} = I$ e $A^{-1} \cdot A = I$, A inversa de $A^{-1} = A$.

- Se $A_{n \times n}$ e $B_{n \times n}$ são matrizes invertíveis, então $AB$ é invertível e sua inversa se dá por $(AB)^{-1} = B^{-1}A^{-1}$.

  > $(AB) \cdot (B^{-1}A^{-1}) = A \cdot (BB^{-1}) \cdot A^{-1} = A \cdot I \cdot A^{-1} = I$ > $(B^{-1}A^{-1}) \cdot (AB) = B^{-1} \cdot (A^{-1}A) \cdot B = B^{-1} \cdot I \cdot B = I$

- Se $A$ é invertível, então a [[Matriz Transposta|transposta]] de $A$ é invertível e sua inversa se dá por $(A^t)^{-1} = (A^{-1})^t$.

  > $A^t \cdot (A^{-1})^t = (A^{-1} \cdot A)^t = I^t = I$ > $(A^{-1})^t \cdot A^t = (A \cdot A^{-1})^t = I^t = I$

- Se $AB = I$, então $BA = I$ e vice-versa.

- $AX = B$ tem única solução se, e somente se, $A$ é invertível.

  > $AX = B$ > $A^{-1} \cdot AX = A^{-1} \cdot B$ > $X = A^{-1}B$

- Se $AX = 0$ tem solução não trivial (todas as variáveis não nulas), $A$ é não invertível.

- Se $AX = B$ tem infinitas ou nenhuma solução, $A$ é não-invertível.

**Exemplo:**

$$
A =
\begin{bmatrix}
1 & 1 & 1 \\
2 & 1 & 4 \\
2 & 3 & 5
\end{bmatrix}
$$

$$
[A \mid I] =
\left[
\begin{array}{ccc|ccc}
1 & 1 & 1 & 1 & 0 & 0 \\
2 & 1 & 4 & 0 & 1 & 0 \\
2 & 3 & 5 & 0 & 0 & 1 \\
\end{array}
\right]
$$

$$
[R \mid S] =
\left[
\begin{array}{ccc|ccc}
1 & 0 & 0 & \frac{7}{5} & \frac{2}{5} & -\frac{3}{5} \\
0 & 1 & 0 & \frac{2}{5} & -\frac{3}{5} & \frac{2}{5} \\
0 & 0 & 1 & -\frac{4}{5} & \frac{1}{5} & \frac{1}{5}
\end{array}
\right]
$$

Como $R = I$, $S$ é a matriz inversa de $A$.

## Condição de Existência de Inversa

$A = (a_{ij})_{n \times n}$ é invertível se, e somente se, $A$ for equivalente por linhas à $I_n$ (obtível por apenas operações elementares).

$A = [A_1 \; A_2 \; \cdot \cdot \cdot \; A_n]$, sendo que $A_i$ é a i-ésima coluna de $A$.

$B = [X_1 \; X_2 \; \cdot \cdot \cdot \; X_n]$, sendo que $X_i$ é a i-ésima coluna de $A$.

$I = [E_1 \; E_2 \; \cdot \cdot \cdot \; E_n]$, sendo que $E_i$ é a i-ésima coluna de $I$.

$A$ é invertível se $\exists B / A \cdot B = I$.

$AB = A \cdot [X_1 \; X_2 \; \cdot \cdot \cdot \; X_n] = [AX_1 \; AX_2 \; \cdot \cdot \cdot \; AX_n] = I = [E_1 \; E_2 \; \cdot \cdot \cdot \; E_n]$

$A \cdot X_j = E_j, \forall j \in [1, n], j \in \mathbb{K}$

**Exemplo:**

$$
A =
\begin{bmatrix}
1 & 2 \\
0 & 1
\end{bmatrix}
$$

$$
A \cdot X_1 =
\begin{bmatrix}
1 \\
0
\end{bmatrix}
$$

$$
A \cdot X_2 =
\begin{bmatrix}
0 \\
1
\end{bmatrix}
$$

$[A \mid E_1 \; E_2 \cdot \cdot \cdot E_n] = [A \mid I]$

Utilizando operações elementares, transformamos $[A \mid I]$ em $[R \mid S]$ tentando obter $R = I$.

Se $R = I$, então todos os SEL tem única solução e $A^{-1} = X = S$.

Se $R \neq I$, então não há inversa de $A$.
