---
title: "Escalonamento"
aliases:
- matriz escalonada
- matrizes escalonadas
- forma escalonada
tags:
- matemática
---
# Escalonamento

Escalonamento é uma técnica utilizada para a solução de [[notes/Sistema de Equações Lineares|Sistemas de Equações Lineares]].

Ela parte do princípio que se $[A|B]$ pode ser obtido a partir de operações elementares sobre $[C|D]$, as suas soluções são as mesmas.

Para realizá-la, dispomos das operações elementares:

- Multiplicação por escalar não nulo
$$L_j \to K \cdot L_j$$
- Troca de linhas
$$L_j \leftrightarrow L_i$$
- Soma de linhas
$$L_j \to L_j + K \cdot L_i$$

## Pivô

O pivô da linha de uma [[notes/Matriz|matriz]] é o primeiro elemento não nulo da linha.

## Passo a Passo

O passo a passo da técnica é:

- Organizar linhas para não ter o pivÇô à direita do pivô da linha imediatamente acima;
- Transformar o primeiro pivô em 1;
- Anular todos os elementos abaixo do primeiro pivô;
- Se não surgir uma linha nula, repita os passos na próxima linha. Se surgir, colocar as linhas nulas no final.

## Matriz Escalonada

A [[notes/Matriz|matriz]] gerada pelo escalonamento é chamada de matriz escalonada. Suas características são:

- Suas linhas nulas estão todas no final;
- Todo pivô está sempre à direita do pivô da linha acima.

## Exemplo

Dado o seguinte [[notes/Sistema de Equações Lineares|SEL]], ache sua matriz escalonada:

$$
\begin{cases}
x + y + z = 3 \\
2x + 3y + 7z = 0 \\
x + 3y - 2z = 17
\end{cases}
$$

Sua matriz aumentada:

$$
\left[
\begin{array}{ccc|c}
1 & 1 & 1 & 3 \\
2 & 3 & 7 & 0 \\
1 & 3 & -2 & 0 \\
\end{array}
\right]
$$

Utilizando a primeira linha, para zerar a primeira coluna das outras linhas, temos que alterar $L_2 \to L_2 - 2L_1$ e $L_3 \to L_3 - L_1$:

$$
\left[
\begin{array}{ccc|c}
1 & 1 & 1 & 3 \\
0 & 1 & 5 & 6 \\
0 & 2 & -3 & 14 \\
\end{array}
\right]
$$

Utilizando a segunda linha, para zerar a segunda coluna das outras linhas, temos que alterar $L_1 \to L_1 - L_2$ e $L_3 \to L_3 - 2L_2$:

$$
\left[
\begin{array}{ccc|c}
1 & 0 & -4 & 9 \\
0 & 1 & 5 & -6 \\
0 & 0 & -13 & 26 \\
\end{array}
\right]
$$

Para transformar o pivô da terceira linha em 1, devemos dividir toda a linha por -13:

$$
\left[
\begin{array}{ccc|c}
1 & 0 & -4 & 9 \\
0 & 1 & 5 & -6 \\
0 & 0 & 1 & -2 \\
\end{array}
\right]
$$

Utilizando a terceira linha, para zerar a terceira coluna das outras linhas, temos que alterar $L_1 \to L_1 + 4L_3$ e $L_2 \to L_2 - 5L_3$:

$$
\left[
\begin{array}{ccc|c}
1 & 0 & 0 & 1 \\
0 & 1 & 0 & 4 \\
0 & 0 & 1 & -2 \\
\end{array}
\right]
$$

Assim, podemos dizer que a única solução para esse SEL é:

$$
\begin{cases}
x = 1 \\
y = 4 \\
z = -2
\end{cases}
$$