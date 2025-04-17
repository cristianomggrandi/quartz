---
title: Limite
aliases:
  - limites
tags:
  - matemática
---

# Limite

Supondo que a [[Função|função]] $f(x)$ esteja definida quando $x$ está próximo de $a$, exceto possivelmente em $a$. Então escrevemos:

$$\lim_{x \to a} f(x) = L$$

O limite de $f(x)$ quando $x$ tende a $a$ é $L$.

**Exemplos:**

$$\lim_{x \to 2} \frac{x^2 - 4}{x - 2} = 4$$

$$\lim_{x \to 0} \sin{\frac{\pi}{x}} \text{ é indefinido.}$$

## Propriedades

Se $f(x)$ e $g(x)$ são duas funções tais que $\lim_{x \to a} f(x)$ e $\lim_{x \to a} g(x)$ existem:

- $\lim_{x \to a} f(x) \pm g(x) = \lim_{x \to a} f(x) \pm \lim_{x \to a} f(x)$
- $\lim_{x \to a} C \cdot f(x) = C \cdot \lim_{x \to a} f(x)$
- $\lim_{x \to a} f(x) \cdot g(x) = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$
- $\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}$
- $\lim_{x \to a} [f(x)]^2 = [\lim_{x \to a} f(x)]^2$
- $\lim_{x \to a} C = C$
- $\lim_{x \to a} x = a$
- $\lim_{x \to a} x^n = a^n$
- $\lim_{x \to a} \sqrt[n]{f(x)} = \sqrt[n]{\lim_{x \to a} f(x)}$

## Teoremas

- [[Teorema do Sanduíche|Teorema do Sanduíche (ou do Confronto)]]

## Limite Lateral

A função $f$ não possui limite quando $x \to 0$.

$$
\begin{cases}
\begin{gather*}
-2x, \text{ se } x < 0\\
x^2, \text{ se } x \geq 0
\end{gather*}
\end{cases}
$$

Porém, podemos definir seus limites laterais, quando $x \to 0$ pela direita ($+$) ou pela esquerda ($-$).

$$\lim_{x \to 1^-} f(x) = 3$$

$$\lim_{x \to 1^+} f(x) = 2$$

$$
\exists \lim_{x \to a} f(x) \iff \lim_{x \to a^-} f(x) = \lim_{x \to a
+} f(x)
$$

## Limites Infinitos

Seja $f$ uma [[Função|função]] definida próximo a $a$, exceto em possivelmente em $a$. Então $\lim_{x \to 2^+} f(x) = \infty$ significa que podemos fazer os valores de $f(x)$ ficarem tão grandes quanto quisermos, bastando para isso tomar $x$ suficientemente próximo a $a$, mas não igual a $a$.

**Exemplo:**
$$\lim_{x \to 0} \frac{1}{x^2}$$
À medida que $x$ se aproxima de 0, o valor de $\frac{1}{x^2}$ é tão grande quanto quisermos.

### Assíntota

Assíntota é uma reta imaginária presente no gráfico de uma função que tem seus valores quão perto for necessário, mas nunca é tocada.

Ela surge quando a função satisfaz uma das seguintes condições:

- $\lim_{x \to a} f(x) = \pm \infty$
- $\lim_{x \to a^-} f(x) = \pm \infty$
- $\lim_{x \to a^+} f(x) = \pm \infty$

## Continuidade

### Contínua em $a$

Uma função $f$ é contínua em $a$ se $\lim_{x \to a} f(x) = f(a)$. Caso contrário, ela é descontínua.

$f$ é contínua à direita em $x = a$ se $\lim_{x \to a^+} f(a)$
$f$ é contínua à esquerda em $x = a$ se $\lim_{x \to a^-} f(a)$

### Contínua em um Intervalo

Uma função $f$ é contínua em um intervalo se for contínua e todos os valores no interior do intervalo.

**Exemplo:**

$f(x) = \frac{1}{x}$ contínua em $(2, 5)$ e $(0, \infty)$ e descontínua em $(-2, 2)$ e $[0, \infty)$.
