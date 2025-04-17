---
title: "Matriz Quadrada"
aliases:
  - matrizes quadradas
tags:
  - matemática
  - matrizes
---

# Matriz Quadrada

Uma matriz quadrada é uma [[Matriz|matriz]] cujo número de linhas e colunas são iguais.

$$A_{m \times n}, m = n$$

## Matriz Diagonal

Matrizes quadradas possuem duas diagonais:

- Diagonal principal
- Diagonal secundária

A principal é formada pelos elementos $a_{ij}, i = j$
A secundária é formada pela reflexão no eixo y

$$
\begin{gathered}
A =
\begin{bmatrix}
	1 & 2 \\
	-1 & 3
\end{bmatrix} \\\\
D. Principal =
\begin{bmatrix}
	\fbox{1} & 2 \\
	-1 & \fbox{3}
\end{bmatrix} \\\\
D. Secundária =
\begin{bmatrix}
	1 & \fbox{2} \\
	\fbox{-1} & 3
\end{bmatrix} \\
\end{gathered}
$$

Uma matriz diagonal é uma matriz quadrada cujos elementos não nulos estão todos na diagonal principal.

**Exemplo:**

$$
A =
\begin{bmatrix}
	2 & 0 \\
	0 & 5
\end{bmatrix}
$$

## Matriz Triangular

Uma matriz triangular é uma matriz quadrada cujos elementos não nulos estão todos na diagonal principal ou acima/abaixo dela.

### Matriz Triangular Superior

Uma matriz triangular superior é uma [[Matriz Quadrada#Matriz Triangular|matriz quadrada]] cujos elementos não nulos estão todos na diagonal principal ou **acima** dela.

$$
A =
\begin{bmatrix}
	2 & 6 & 3 \\
	0 & 5 & 4 \\
	0 & 0 & 1
\end{bmatrix}
$$

### Matriz Triangular Inferior

Uma matriz triangular é uma [[Matriz Quadrada#Matriz Triangular|matriz quadrada]] cujos elementos não nulos estão todos na diagonal principal ou **abaixo** dela.

$$
A =
\begin{bmatrix}
	1 & 0 & 0 \\
	4 & 5 & 0 \\
	2 & 6 & 3 \\
\end{bmatrix}
$$
