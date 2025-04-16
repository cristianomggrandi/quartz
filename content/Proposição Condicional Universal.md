---
title: Proposição Condicional Universal
aliases: 
tags:
  - matrizes
  - lógica
---
# Proposição Condicional Universal

Considera-se que a forma de [[notes/Proposição|proposição]] mais importante em [[notes/Matemática|matemática]] é a proposição [[notes/Se Então (Operador Lógico)|condicional]] universal.

$\forall x \in D, P(x) \implies Q(x)$

**Exemplo:**

$\forall x \in \mathbb{R}$, se $x > 2$, então $x^2 > 4$.

## Negação

$\lnot(\forall x, P(x) \implies Q(x)) \equiv \exists x \mid P(x) \land \lnot Q(x)$

## Modus Ponens Universal

Assim como uma proposição comum, a proposição condicional universal também possui um [[notes/Modus Ponens|Modus Ponens]].

$$
\begin{gathered}
\forall x \in D, P(x) \implies Q(x) \\
P(a) \\
\therefore Q(a)
\end{gathered}
$$

**Exemplo:**

$$
\begin{gathered}
\forall x \in \mathbb{N} \text{ , se x é par, então } x^2 \text{ é par} \\
k \in \mathbb{K}, k \text{ é par} \\
\therefore k^2 \text{ é par}
\end{gathered}
$$