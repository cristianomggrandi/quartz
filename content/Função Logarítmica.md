---
title: Função Logarítmica
aliases:
  - funções logarítmicas
tags:
  - matemática
---

# Função Logarítmica

A [[Função Exponencial|função exponencial]] $f(x) = a^x$, $a>0$, $a \neq 1$ é uma bijeção de $\mathbb{R}$ em $\mathbb{R_*^+}$.

Sua [[Função|função]] inversa é chamada função logarítmica de base $a$ ($a > 0$, $a \neq 1$).

$$
\log_a x : \mathbb{R_*^+} \to \mathbb{R}
$$

$$a^b = c \iff b = \log_a c$$

## Propriedades

$\log_a (x \cdot y) = \log_a x + \log_a y$
$\log_a (\frac{x}{y}) = \log_a x - \log_a y$
$\log_a x^k = k\log_a x$

## Mudança de Base

Sejam $a, b \in (0, 1) \cup (1, \infty)$ e $x \in (0, \infty)$. Então

$$\log_b x = \frac{\log_a x}{\log_a b}$$

## Funções Logarítmicas

Para $\log_a b$, é necessário que $b > 0, a > 0, a \neq 1$.

**Exemplo:**

Encontre o domínio de $f(x) = \log_{10} (x^2 - 5x + 6)$.

Condições:

- $x + 1 > 0 \iff x > -1$
- $x + 1 \neq 1 \iff x \neq 0$
- $x^2 - 5x + 6 > 0 \iff x \in (-\infty, 2)\cup(3, \infty)$

$D = (-1, 0)\cup(0, 4)$

## Equações Logarítmicas

**Exemplo:**

$\log_{x - 1} 6 = 1 \iff (x - 1)^1 = 6 \iff x - 1 = 6 \iff x = 7$

**Exemplo 2:**

$\log_{x + 2} (2x^2 + x) = 1$
$2x^2 + x = (x + 2)^1 \iff 2^2 = 2 \iff x^2 = 1 \iff x = \pm 1$

Condições

- $x + 2 > 0 \iff x > -2$
- $x + 2 \neq 1 \iff x \neq -1$
- $2x^2 + x > 0 \iff x \in \left(-\infty, -\frac{1}{2}\right)\cup(0, \infty)$

$x = 1$
