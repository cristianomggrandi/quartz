---
title: Demonstração por Contradição
aliases:
  - demonstrações por contradição
  - prova por contradição
  - provas por contradição
tags:
  - matemática
  - lógica
---
# Demonstração por Contradição

Data: 04/08/2023

Uma demonstração por contradição, ou por absurdo, utiliza do [[notes/Princípio do Terceiro Excluído|Princípio do Terceiro Excluído]] para descobrir a validade de uma afirmação. Para isso, assumimos ela como falsa e, caso cheguemos em algum absurdo, a afirmação é verdadeira.

Para provar $\forall x \in D: P(x) \implies Q(x)$, podemos provar que sua negação $\exists x \in D: P(x) \land \lnot Q(x)$ é impossível.

**Exemplo:** Se $a$ e $b$ são números reais não negativos, então $\frac{a+b}{2} \ge \sqrt{ab}$.

Supondo, por absurdo, que existam $a,b \in \mathbb{R}$, $a,b \geqslant 0$, tais que $\frac{a+b}{2} < \sqrt{ab}$, então

$$
\begin{gathered}
a + b < 2\sqrt{ab} \\
a - \sqrt{ab} + b < 0 \\
(\sqrt{a} - \sqrt{b})^2 < 0 \\
\end{gathered}
$$

Como é impossível haver um número $x, x \in \mathbb{R}$ tal que $x^2 < 0$, podemos concluir que
$$\frac{a+b}{2} \ge \sqrt{ab}$$

**Exemplo 2:** $\sqrt{2}$ é irracional

Supondo, por absurdo, que $\sqrt{2}$ é racional. Então $\sqrt{2} = \frac{p}{q}$, $p,q \in \mathbb{R}, q \neq 0$ e $p$ e $q$ não possuem nenhum fator em comum.

$$
\begin{gathered}
\sqrt{2} = \frac{p}{q} \\
2 = \frac{p^2}{q^2} \\
2q^2 = p^2
\end{gathered}
$$

Como sabemos que, se $p^2$ é par, $p$ é par, $p = 2r, r \in \mathbb{Z}$.

$$
\begin{gathered}
\sqrt{2} = \frac{p}{q} = \frac{2r}{q} \\
2 = \frac{4r^2}{q^2} \\
2q^2 = 4r^2 \\
q^2 = 2r^2
\end{gathered}
$$

Como $q^2$ é par, $q$ é par. Assim, não podemos dizer que $p$ e $q$ não possuem nenhum fator em comum.

Logo, $\sqrt{2}$ é irracional. $\blacksquare$