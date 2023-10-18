---
title: Predicado
aliases:
  - predicados
tags:
  - matemática
  - lógica
---

# Predicado

Em [[notes/Lógica|lógica]], se obtém um predicado ao retirar o sujeito da [[notes/Proposição|proposição]]. É uma sentença que contém um número finito de variáveis e se torna uma proposição quando variáveis são substituídas por valores específicos.

**Exemplo:**

|      Predicado      |       Proposição       |
|:-------------------:|:----------------------:|
| $P(x) = X$ é mortal | $p$: Sócrates é mortal |

O predicado é uma [[notes/Função|função]] de uma ou mais variáveis que se torna uma proposição quando a(s) variável(is) assumem um valor no domínio.

Se $P(x)$ é um predicado e $x$ tem domínio $D$, o conjunto verdade de $P(x)$ é o conjunto de todos os elementos de $D$ que fazem $P(x)$ verdadeiro quando substituído por $x$. O conjunto veradde de $P(x)$ é denotado por:

$$\lbrace x \in D \mid P(x)\rbrace$$

**Exemplo:**

$$
\begin{gathered}
P(x) = x \text{ é um fator de 8}\\
D: \mathbb{N}\\
\text{Conjunto verdade: } \lbrace1, 2, 4, 8\rbrace
\end{gathered}
$$

## Notação

Para denotar que cada elemento no conjunto verdade de $P(x)$ está no conjunto verdade de $Q(x)$, escrevemos $P(x) \implies Q(x)$.

**Exemplo:**

Considere $D: \mathbb{Z}^+$ e as seguintes proposições:

|         Proposição         | Conj. Verdade |
|:--------------------------:|:-------------:|
| $P(x): x$ é um fator de 8  | {1, 2, 4, 8}  |
| $Q(x): x$ é um fator de 4  |   {1, 2, 4}   |
| $R(x): x < 5$ e $x \neq 3$ |   {1, 2, 4}   |

Podemos afirmar que:

$$
\begin{gathered}
	Q(x) \iff R(x) \\
	Q(x) \implies P(x) \\
	R(x) \implies P(x)
\end{gathered}
$$

Para denotar se há um item ou se são todos os itens do domínio que satisfazem a propriedade, utiliza-se os [[notes/Quantificador|quantificadores]].