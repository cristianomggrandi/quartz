---
title: Vetor
aliases:
  - vetores
  - vetorial
  - vetoriais
tags:
  - matemática
  - álgebra-linear
  - geometria
---

# Vetor

Um vetor é uma classe de [[Segmento Orientado|segmentos orientados]] equipolentes.

$$\vec v: [\vec{AB}] = \lbrace \vec{XY}; \vec{XY} \sim \vec{AB} \rbrace$$

Seja $\vec{AB}$ um representante qualquer do vetor $\vec v$, as coordenadas de $\vec v$ são:

$$A = (a_1, a_2, a_3) \text{ e } B = (b_1, b_2, b_3)$$

$$\vec v = (a_1 - a_1, b_2 - a_2, b_3 - a_3)$$

## Norma

A norma ($\Vert \vec v \Vert$) de um vetor é a distância da origem para a extremidade.

$$\Vert \vec v \Vert = \sqrt{v_1^2 + v_2^2 + v_3^2}, \vec v \in \mathbb{R}^3$$

## Operações com Vetores

$\vec u = (u_1, u_2, u_3)$

$\vec v = (v_1, v_2, v_3)$

### Adição

$$\vec u + \vec v = (u_1 + v_1, u_2 + v_2, u_3 + v_3)$$

### Multiplicação por Escalar

$$\lambda \vec v = (\lambda v_1, \lambda v_2, \lambda v_3)$$

**Exemplo:** Determine o ponto médio $M(x, y)$ de um segmento de reta $\vec{AB}$, sendo $A(a_1, a_2)$ e $B(b_1, b_2)$.

$$\vec{AM} = \vec{MB} \iff (x - a_1, y - a_2) = (b_1 - x, b_2 - y)$$
$$x - a_1 = b_1 - x \iff x = \frac{a_1 + b_1}{2}$$
$$y - a_2 = b_2 - y \iff y = \frac{a_2 + b_2}{2}$$

**Exemplo 2:** Determine a extremidade do segmento que representa $\vec v = (2, 5)$, sabendo que sua origem é $(-1, 3)$.

$$\vec{AB} = \vec v \iff (x + 1, y - 3) = (2, 5)$$
$$x + 1 = 2 \iff x = 1$$
$$y - 3 = 5 \iff y = 8$$
$$B = (1, 8)$$

#### Propriedades Operacionais

|                Propriedade                 |                                   Operação                                   |
| :----------------------------------------: | :--------------------------------------------------------------------------: |
|               Comutatividade               |                     $\vec u + \vec v = \vec v + \vec u$                      |
|              Associatividade               |          $(\vec u + \vec v) + \vec w = \vec u + (\vec v + \vec w)$           |
|         Elemento neutro da adição          | $\exists\vec{0}; \vec v + \vec{0} = \vec v, \forall \vec v \in \mathbb{R}^3$ |
|        Elemento simétrico na adição        |  $\exists \vec v, \vec{-v} \in \mathbb{R}^3; \vec v + (\vec{-v}) = \vec{0}$  |
|          Distributiva do escalar           |        $\lambda (\vec u + \vec v) = \lambda \vec u + \lambda \vec v$         |
|           Distributiva do vetor            |    $(\lambda_1 + \lambda_2) \vec v = \lambda_1 \vec v + \lambda_2 \vec v$    |
| Associatividade na distributiva do escalar |        $\lambda_1 (\lambda_2 \vec v) = (\lambda_1 \lambda_2) \vec v$         |
| Elemento neutro na multiplicão por escalar |                          $1 \cdot \vec v = \vec v$                           |

### Produto Escalar (Produto Interno)

O produto escalar é denotado por $\vec u \cdot \vec u$ ou $\langle \vec u, \vec v \rangle$.

$$(\vec u \cdot \vec v): \mathbb{R}^n \cdot \mathbb{R}^n \to \mathbb{R}$$

$$\vec u \cdot \vec v = u_1 \cdot v_1 + u_2 \cdot v_2 + \cdots + u_n \cdot v_n$$

Esta operação está estreitamente ligada ao ângulo formado pelos vetores.

**Exemplo:** $\vec u = (-1, 2, 3)$ e $\vec v = (2, 0, -4)$.

$$\vec u \cdot \vec v = (-1) \cdot 2 + 2 \cdot 0 + 3 \cdot (-4) = -14$$

Note a ligação entre a norma do vetor e seu produto escalar consigo mesmo:

$$\Vert \vec v \Vert = \sqrt{v_1^2 + v_2^2 + v_3^2} \iff \Vert \vec v \Vert^2 = \langle \vec v, \vec v \rangle$$

#### Interpretação Geométrica

Sejam $\vec u, \vec v \in \mathbb{R}^n e \theta = \angle (\vec u, \vec v)$, então

$$\langle \vec u, \vec v \rangle = \Vert \vec u \Vert \Vert \vec v \Vert \cos \theta$$

Usando isso, podemos provar que:

- $\langle \vec u, \vec v \rangle > 0 \iff \theta$ é agudo
- $\langle \vec u, \vec v \rangle = 0 \iff \vec u \perp \vec v$
- $\langle \vec u, \vec v \rangle < 0 \iff \theta$ é obtuso

**Prova:**

$$\Vert \vec u - \vec v \Vert^2 = (\vec u - \vec v)(\vec u - \vec v) = \vec u (\vec u - \vec v) - \vec v (\vec u - \vec v)$$
$$\vec u\vec u - \vec u\vec v - \vec v\vec u + \vec v\vec v = \Vert \vec u \Vert^2 - 2(\vec u\vec v) + \Vert \vec v \Vert^2$$
[[Lema|Lema]]: $\Vert \vec u - \vec v \Vert^2 = \Vert \vec u \Vert^2 - 2(\vec u\vec v) + \Vert \vec v \Vert^2$

Por meio da Lei dos Cossenos, podemos obter que:

$$\Vert \vec u - \vec v \Vert^2 = \Vert \vec u \Vert^2 + \Vert \vec v \Vert^2 - 2 \Vert \vec u \Vert \Vert \vec v \Vert \cos \theta$$
$$\Vert \vec u \Vert^2 - 2(\vec u\vec v) + \Vert \vec v \Vert^2 = \Vert \vec u \Vert^2 + \Vert \vec v \Vert^2 - 2 \Vert \vec u \Vert \Vert \vec v \Vert \cos \theta$$
$$\Vert \vec u - \vec v \Vert = \langle \vec u, \vec v \rangle = \Vert \vec u \Vert \Vert \vec v \Vert \cos \theta$$

Além disso:

$$\cos \theta = \frac{\vec u \cdot \vec v}{\Vert \vec u \Vert \Vert \vec v \Vert} \iff \theta = \arccos \left( \frac{\vec u \cdot \vec v}{\Vert \vec u \Vert \Vert \vec v \Vert} \right)$$

#### Propriedades Operacionais

- $\langle \vec u, \vec v \rangle = \langle \vec v, \vec u \rangle$
- $\langle \vec u, \vec v + \vec w \rangle = \langle \vec u, \vec v \rangle + \langle \vec u, \vec w \rangle$
- $\langle \vec v, \vec v \rangle \geq 0$
- $\langle \vec v, \vec v \rangle = 0 \iff \vec v = \vec{0}$

### Produto Vetorial

Sejam $\vec u, \vec v \in \mathbb{R}^3$. O produto vetorial é denotado por $\vec u \times \vec v$.

- $\Vert \vec u \times \vec v \Vert = \Vert \vec u \Vert \Vert \vec v \Vert \sin \theta$, para $0 \leq \theta \leq \pi$
- $\vec u \times \vec v$ é ortogonal a $\vec u$ e $\vec v$.
- O sentido é dado pela regra da mão direita.

#### Propriedades Operacionais

1. Se $\vec v = \alpha \vec u, \alpha \in \mathbb{R}$, então $\vec u \times \vec v = 0$.
2. $\vec u \times \vec v = \vec{-v} \times \vec u$
3. $\vec u \times (\vec v + \vec w) = \vec u \times \vec v + \vec u \times \vec w$
4. $(\vec u + \vec v) \times \vec w = \vec u \times w + \vec v \times \vec w$
5. $\vec u \times K \vec v = K\vec u \times \vec v = K(\vec u \times \vec v)$
6. Se $\vec u \times \vec v = 0$, então $\vec u$ ou $\vec v$ são nulos ou $\vec u \parallel \vec v$
7. $\Vert \vec u \times \vec v \Vert^2 = \Vert \vec u \Vert^2 \Vert \vec v \Vert^2 - (\langle \vec u, \vec v \rangle)^2$

**Prova do item 7:** TODO

As coordenadas do vetor $\vec u \times \vec v$ são dadas por:

$$
\det (
\begin{bmatrix}
\vec i & \vec j & \vec k \\
u_1 & u_2 & u_3 \\
v_1 & v_2 & v_3
\end{bmatrix}
)
=
(u_2v_3 - u_3v_2) \vec i - (u_1v_3 - u_3v_1) \vec j + (u_1v_2 - u_2v_1) \vec k
$$

$$\vec u \times \vec v = (u_2v_3 - u_3v_2, - (u_1v_3 - u_3v_1), u_1v_2 - u_2v_1)$$

#### Interpretação Geométrica

Sejam $\vec u$ e $\vec v$ vetores não paralelos e $\theta$ o ângulo entre eles, a área do paralelogramo formado é igual à norma do produto vetorial.

$$Área = \Vert \vec u \times \vec v \Vert$$

## Projeção Ortogonal

A projeção ortogonal ($\vec w$) de $\vec u$ na direção de $\vec v$ é a "sombra" de $\vec u$ em $\vec v$.

$$\vec w = proj_{\vec v} \vec u = K \vec v = \frac{\langle \vec u, \vec v \rangle}{\Vert \vec v \Vert^2} \cdot \vec v$$

**Prova:**

$$\Vert \vec w \Vert = \Vert K \vec v \Vert = \vert K \vert \Vert \vec v \Vert \iff \vert K \vert = \frac{\Vert \vec w \Vert}{\Vert \vec v \Vert}$$
$$\cos \theta = \frac{\Vert \vec w \Vert}{\Vert \vec v \Vert} \iff \Vert \vec w \Vert = \Vert \vec v \Vert \vert \cos \theta \vert = \Vert \vec v \Vert \cdot \frac{\vert \vec u \cdot \vec v \vert}{\Vert \vec u \Vert \Vert \vec v \Vert} \iff \Vert \vec w \Vert = \frac{\vert \vec u \cdot \vec v \vert}{\Vert \vec v \Vert^2}$$
$$\vert K \vert = \frac{\vert \vec u \cdot \vec v \vert}{\Vert \vec v \Vert^2} \iff K = \frac{\vec u \cdot \vec v}{\Vert \vec v \Vert^2} = \frac{\langle \vec u, \vec v \rangle}{\Vert \vec v \Vert^2}$$

Logo:

$$proj_{\vec v} \vec u = \frac{\langle \vec u, \vec v \rangle}{\Vert \vec v \Vert^2} \cdot \vec v$$
