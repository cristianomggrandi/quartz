---
title: Indução Matemática
aliases:
  - induções matemáticas
tags:
  - matemática
---
# Indução Matemática

Técnica usada para provar afirmações para todos os números inteiros positivos $n$.

## Passos

O Princípio da Indução Matemática possui dois passos:

- **Passo Base:** Prove que a propriedade é válida para o 1º elemento da série ($n_o$)
- **Passo Indutivo:** Suponha que a propriedade seja válida para $K$. Usando essa informação, prove que a propriedade também é válida para $K + 1$.

Provados os passos, a propriedade é válida no domínio.

**Exemplo:**

$$\sum_{i = 1}^{n} i = 1 + 2 + 3 + \cdots + n = \frac{n(n + 1)}{2}, i \in \mathbb{N}$$

- Passo Base:

$$\sum_{i = 1}^{n_o} i = \frac{n_o(n_o + 1)}{2} = \frac{1(1 + 1)}{2} = 1$$

- Passo Indutivo:

$$\text{Supondo } \sum_{i = 1}^{k} i = \frac{k(k + 1)}{2}, \text{ queremos provar } \sum_{i = 1}^{k + 1} i = \frac{(k + 1)(k + 2)}{2}$$
$$\sum_{i = 1}^{k + 1} i = 1 + 2 + 3 + \cdots + k + (k + 1)$$
$$\sum_{i = 1}^{k} i + (k + 1)$$
$$\frac{k(k + 1)}{2} + (k + 1)$$
$$\frac{k(k + 1) + 2(k + 1)}{2} = \frac{(k + 1)(k + 2)}{2}$$

**Exemplo 2:**

$$\sum_{i = 1}^{n} (2i - 1) = 1 + 3 + 5 + \cdots + (2n - 1) = n^2, i \in \mathbb{N}$$

- Passo Base:

$$\sum_{i = 1}^{n_o} (2i - 1) = n_o^2 = 1^2 = 1$$

- Passo Indutivo:

$$\text{Supondo } \sum_{i = 1}^{k} (2i -1) = k^2, \text{ queremos provar } \sum_{i = 1}^{k + 1} (2i - 1) = (k + 1)^2$$
$$\sum_{i = 1}^{k + 1} i = 1 + 3 + 5 + \cdots + (2k - 1) + (2(k + 1) - 1)$$
$$\sum_{i = 1}^{k} (2i - 1) + (2k + 1)$$
$$k^2 + (2k + 1)$$
$$(k + 1)^2$$

**Exemplo 3:**

$$\sum_{i = 1}^{n} i^2 = 1^2 + 2^2 + 3^2 + \cdots + n^2 = \frac{n(n + 1)(2n + 1)}{6}, i \in \mathbb{N}$$

- Passo Base:

$$\sum_{i = 1}^{n_o} i^2 = n_o^2 = \frac{n_o(n_o + 1)(2n_o + 1)}{6} = \frac{1(1 + 1)(2(1) + 1)}{6} = 1$$

- Passo Indutivo:

$$\text{Supondo } \sum_{i = 1}^{k} i^2 = \frac{k(k + 1)(2k + 1)}{6}$$
$$\text{Queremos provar } \sum_{i = 1}^{k + 1} i^2 = \frac{(k + 1)(k + 2)(2k + 3)}{6}$$
$$\sum_{i = 1}^{k + 1} i^2 = 1^2 + 2^2 + 3^2 + \cdots + k^2 + (k + 1)^2$$
$$\sum_{i = 1}^{k} i^2 + (k + 1)^2$$
$$\frac{k(k + 1)(2k + 1)}{6} + (k + 1)^2$$
$$\frac{k(k + 1)(2k + 1) + 6(k + 1)^2}{6}$$
$$\frac{(k + 1)(k(2k + 1) + 6(k + 1))}{6} = \frac{(k + 1)(2k^2 + 7k + 6)}{6}$$
$$\frac{(k + 1)(k + 2)(2k + 3)}{6}$$