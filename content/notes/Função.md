---
title: "Função"
alias: funções
tags:
- matemática
---
# Função

Data: 05/08/2023

Em [[notes/Matemática|matemática]], uma função é uma associação dos elementos de dois [[notes/Conjunto|conjuntos]].

**Definição:** Seja $C$ e $D$ dois conjuntos. Uma função $f\colon D \to C$ é uma relação que associa a cada elemento $x$ do conjunto $D$ (domínio), um elemento $f(x)$ do conjunto $C$ (contradomínio).

*Obs: Nem toda relação entre números são funções. (Ex.: $x^2 + y^2 = 16$)*

## Domínio e Contradomínio

Quando o domínio não for especificado, o domínio (natural) de $f$ é o subconjunto de $\mathbb{R}$ de todos os valores para os quais ela estiver definida.

**Exemplo:** Dada a função $f$, tal que
$$f(x) = \frac{1}{1-x}$$

Seu domínio $D$ pode ser descrito da segunte forma:
$$D = \mathbb{R} \setminus \{-1, 1\} = (-\infty, -1)\cup(-1, 1)\cup(1, \infty)$$

## Imagem

Dada a função $f\colon D \to C$, o valor $f(x)$ é chamado **imagem** de $x$. O conjunto de todas as imagens de D é chamado de conjunto imagem.

$$Im(f) = {f(x) \mid x \in D}$$

**Exemplo:** Dada a função $f(x) = x+2$, com domínio definido por $[2, 4]$ e contradomínio nos $\mathbb{R}$:

- A imagem de 8 é 10
- $Im(f) = [4,6]$

## Gráfico de Função

O gráfico de $f$ é o conjunto dos pontos $(x,y)$ do plano cartesiano tais que $y = f(x)$.

## Simetria

Se, para todo $x \in D$, $f(-x) = f(x)$, $f$ é uma função **PAR** . Ou seja, é simétrico no eixo $y$.

Se, para todo $x \in D$, $f(-x) = -f(x)$, $f$ é uma função **ÍMPAR** . Ou seja, é simétrico no eixo $x$.

## Raízes

As raízes, ou zeros, de uma função são os valores de $x$ no domínio tais que $f(x) = 0$.

## Crescente e Decrescente

Seja $f$ uma função definida no intervalo $I$. Dizemos que $f$ é **crescente** em $I$ se, sempre que $x_1 < x_2$ e $f(x_1) \leq f(x_2)$ e **decrescente** se $f(x_1) \geq f(x_2)$.

**Exemplo:** $f(x) = x^2$ é crescente em $[1, 5]$ e decrescente em $[-5, 1]$. Já em $[-3, 3]$ ela não é nem crescente nem decrescente.

## Injetora

Seja $f$ uma função, ela é **injetora** (ou injetiva) quando
$$x_1 \ne x_2 \Rightarrow f(x_1) \ne f(x_2) \ \forall x_1, x_2 \in D$$

## Tipos de Funções

- [[notes/Função Polinomial|Polinomial]]
- [[notes/Função Raiz|Função Raiz]]
- [[notes/Função Recíproca|Função Recíproca]]
- [[notes/Função Racional|Função Racional]]
- [[notes/Função Exponencial|Função Exponencial]]