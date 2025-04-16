---
title: Conjunto
aliases:
  - conjuntos
tags:
  - matemática
---
# Conjunto

Um conjunto é uma adição contável de elementos.

**Exemplo:** $A = \lbrace0, 1, 2, 5\rbrace$

## Relações de Conjuntos

### Interseção (e)

Conjunto que possui os elementos presentes em ambos os conjuntos.

$$A \cap B$$

### União (ou)

Conjunto que possui os elementos presentes nos conjuntos, retirando duplicatas.

$$A \cup B$$

### Interseção (não)

Conjunto que possui todos os elementos presentes no [[notes/Espaço Amostral|espaço amostral]] ausentes no conjunto.

$$A^c$$

### Contém

Os elementos do conjunto $A$ estão no conjunto $B$.

$$A \subset B \text{ (Contém)}$$
$$A \subseteq B \text{ (Contém e pode ser igual)}$$
$$A \subsetneq B \text{ (Contém e não pode ser igual)}$$

## Leis de De Morgan

$$(A \cap B)^c = A^c \cup B^c$$

$$(A \cup B)^c = A^c \cap B^c$$

## Partição de Conjuntos

$P(A)$: Todos os subconjuntos de $A$ mais $\varnothing$.

**Exemplo:**

$A = \lbrace1, 2, 3, 4\rbrace$

$P(A) = \lbrace\varnothing, 1, 2, 3, 4, (1, 2), (1, 3), (1, 4), (2, 3), (2, 4), (3, 4), (1, 2, 3), (1, 2, 4), (1, 3, 4), (2, 3, 4), (1, 2, 3, 4)\rbrace$

## Contagens

$\#A$: Número de elementos em $A$ (cardinalidade do conjunto $A$).