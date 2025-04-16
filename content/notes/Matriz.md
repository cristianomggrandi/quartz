---
title: "Matriz"
aliases:
- matrizes
- matricial
tags:
- matemática
- matrizes
---
# Matriz

Matriz é uma tabela de elementos composta por linhas e colunas.

A matriz $A$ é notada por $A_{m \times n}$ ou $[a_ij]_{m \times n}$ e tem $m$ linhas e $n$ colunas.

Um elemento é representado por $a_ij$ e ele se localiza na linha $i$ e coluna $j$.

**Exemplo:** Dada a matriz $A_{2  \times 2}$
$$
\begin{gathered}
A_{2 \times 2} =
\begin{bmatrix}
	1 & \fbox{2} \\
	-1 & 3
\end{bmatrix} \\
a_{12} = 2
\end{gathered}
$$

## Tipos de Matriz

- [[notes/Matriz Quadrada|Matriz quadrada]]
- [[notes/Matriz Nula|Matriz nula]]
- [[notes/Matriz Linha|Matriz linha]]
- [[notes/Matriz Coluna|Matriz coluna]]
- [[notes/Matriz Quadrada#Matriz Diagonal|Matriz quadrada]]
- [[notes/Matriz Quadrada#Matriz Triangular|Matriz triangular]]
- [[notes/Matriz Identidade|Matriz identidade]]

## Matrizes Relacionadas

- [[notes/Matriz Transposta|Matriz transposta]]
- [[notes/Matriz Inversa|Matriz inversa]]

## Operações com Matrizes

### Adição

Para se adicionar duas matrizes, elas devem obrigatoriamente ser da mesma ordem (número de linhas e número de colunas iguais) e o resultado será também da mesma ordem.

**Exemplo:**
Sejam A e B duas matrizes de ordem $m$ por $n$. A soma de A + B é o resultado da soma de seus elementos na mesma posição.

$$
\begin{gathered}
C = A + B \\
[c_{ij}] = [a_{ij} + b_{ij}] \\
\end{gathered}
$$

### Subtração

$A - B := A + (-1)B$

### Multiplicação

#### Por Número Escalar

Para se multiplicar uma matriz por um número escalar $λ$, deve-se multiplicar todos os seus elementos por aquele número.

$$
\begin{gathered}
C = λA \\
[c_{ij}] = [λ \times a_{ij}] \\
\end{gathered}
$$

#### Por Matriz

Para se multiplicar duas matrizes, a primeira matriz deve ter o número de colunas igual ao número de linhas da segunda matriz. O resultado terá o número de linhas da primeira e o número de colunas da segunda.

$$
\begin{gathered}
C_{m \times n} = A_{m \times k} \times B_{k \times n} \\
\end{gathered}
$$

Sejam A e B duas matrizes de ordem $m$ por $n$. A multiplicação de $A \cdot B$ é o resultado da seguinte expressão:

$$
\sum_{l = 1}^{k} a_{il} \cdot b_{lj} = a_{i1} \cdot b_{1j} + a_{i2} \cdot b_{2j} + \cdot \cdot \cdot \ + a_{ik} \cdot b_{kj} 
$$

**Exemplo:**
$$
\begin{gathered}
A =
\begin{bmatrix}
	1 & -1 & 2 \\
	2 & 0 & -3
\end{bmatrix}
\
B =
\begin{bmatrix}
	1 & 0 & 3 \\
	1 & -2 & 0 \\
	1 & 0 & -4
\end{bmatrix} \\\\
[c_{11}] = 1 \cdot 1 + (-1) \cdot 1 + 2 \cdot 1 = 2
\end{gathered}
$$

### Potenciação

$$A^k := \underbrace{A \times A \times \cdot \cdot \cdot \times A}_{\text{k vezes}}$$

### Propriedades Operacionais

Sendo $A$ e $B$ matrizes e $λ$ um número escalar, temos:

| Propriedade                       | Operação                     |
| --------------------------------- | ---------------------------- |
| Comutatividade                    | $A + B = B + A$              |
| Associatividade                   | $(A + B) + C = A + (B + C)$  |
| ?                                 | $A + 0 = A$                  |
| Distribuição do escalar           | $λ(A + B) = λA + λB$         |
| Distribuição da matriz            | $A(λ_1 + λ_2) = λ_1A + λ_2A$ |
| Distribuição de matriz por matriz | $A(B + C) = AB + AC$         |
| ?                                 | $0 \cdot A = 0$              |
| Associatividade multiplicativa    | $(AB)C = A(BC)$              |
| Assoc. mult. por escalar          | $n(AB) = (nA)B$              |

## Determinante

Toda matriz possui um [[notes/Determinante|determinante]], que, entre outras coisas, permite definir se há uma [[notes/Matriz Inversa|matriz inversa]].