---
title: "Função Polinomial"
aliases:
- funções polinomiais
- polinômio
- polinômios
- polinomial
- polinomiais
tags:
- matemática
---
# Função Polinomial

Funções polinomiais são [[notes/Função|funções]] que podem ser escritas na forma

$$f(x) = a_nx^n + a_{n-1}x^{n-1} + a_{n-2}x^{n-2} \cdot \cdot \cdot \ a_1x^1 + a_0, \ a \in \mathbb{R}, n\in \mathbb{N}$$

$f$ é [[notes/Função#Simetria|par]] se $n$ for par, e [[notes/Função#Simetria|ímpar]] se $n$ for ímpar.

Uma função polinomial $f$ de grau $n$ tem no máximo $n$ raízes.

Considerando $r_n$ como a n-ésima raiz da função $p(x)$, $p$ pode ser escrita da forma

$$
p(x) = a_n (x - r_1) (x - r_2) \cdot \cdot \cdot (x - r_n)
$$

## Grau

O grau de uma função polinomial se dá pelo maior expoente associado à variável.

### 1º Grau

Uma função polinomial de 1º grau se dá na forma

$$f(x) = ax + b$$

$$a \neq 0$$

#### Propriedades

- Domínio: $\mathbb{R}$
- Imagem: $\mathbb{R}$
- Raiz: $x = \frac{-b}{a}$
- Crescente se $a > 0$ e decrescente se $a < 0$
- Encontra o eixo $y$ em $(0, b)$

### 2º Grau

Uma função polinomial de 2º grau se dá na forma

$$f(x) = ax^2 + bx + c$$

$$a \neq 0$$

#### Propriedades

- Domínio: $\mathbb{R}$
- Raiz: $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$, $b^2 - 4ac \geq 0$
- Crescente se $a > 0$ e decrescente se $a < 0$
- Encontra o eixo $y$ em $(0, c)$

## Divisão de Polinômios

A divisão entre dois polinômios pode ser calculada dividindo o $x$ de maior grau do dividendo pelo $x$ de maior grau do divisor, multiplicando o resultado por todo o divisor e subtraindo do dividendo.

Isso suscessivamente até o resto não possuir mais a variável x de maior ou igual grau que o divisor.

**Exemplo:**

$$\frac{6x^3 - 2x^2 + x + 3}{x + 1}$$

O resultado da divisão do $x$ de maior grau do dividento ($6x^3$) pelo $x$ de maior grau do divisor ($x^1$) tem resultado $6x^2$. Multiplicando pelo dividendo ($x + 1$) obtemos $6x^3 - 6x^2$. Subtraindo do dividendo, obtemos $-8x^2 + x + 3$. Note que o grau do polinômio restante diminuiu.

Fazendo isso sucessivamente enquanto possível, obtemos o resultado $6x^2 - 8x + 9$ e o resto $-6$, ou seja:

$$\frac{6x^3 - 2x^2 + x + 3}{x + 1} = 6x^2 - 8x + 9 + \frac{-6}{x + 1}$$

Partindo do pressuposto que já sabemos $r_1$ para a função

$$f(x) = a_n (x - r_1) (x - r_2) \cdot \cdot \cdot (x - r_n)$$

Podemos dividir $f(x)$ por $x - r_1$ para diminuir o grau do polinômio, facilitando obter as outras raízes.