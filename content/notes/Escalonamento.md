---
title: "Escalonamento"
aliases:
- 
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
$$L_j \iff L_i$$
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