---
title: Teorema do Sanduíche
aliases: 
tags:
  - matemática
---
# Teorema do Sanduíche (ou do Confronto)

O [[notes/Teorema|Teorema]] do Sanduíche afirma que, se existem os [[notes/Limite|limites]] $\lim_{x \to a} f(x)$ e $\lim_{x \to a} g(x)$ e $f(x) \leq g(x)$ quando $x$ está próximo a $a$, então $\lim_{x \to a} f(x) \leq \lim_{x \to a} g(x)$.

Logo, se

- $f(x) \leq g(x) \leq h(x)$
- $\lim_{x \to a} f(x) = L = \lim_{x \to a} h(x)$

Então

$$\lim_{x \to a} g(x) = L$$

**Exemplo:**

$g(x) = x^2 \sin \frac{\pi}{x}$
$-x^2 \leq x^2 \sin \frac{\pi}{x} \leq x^2$
$\lim_{x \to 0} -x^2$
$\lim_{x \to 0} x^2$

Então, pelo Teorema do Sanduíche:

$$\lim_{x \to 0} \left[x^2 \sin \frac{\pi}{x}\right] = 0$$
