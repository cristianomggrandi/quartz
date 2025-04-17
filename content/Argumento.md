---
title: "Argumento"
aliases:
  - argumentos
tags:
  - matemática
  - lógica
---

# Argumento

Em [[Lógica|lógica]], um argumento é uma sequência de afirmações que termina com uma conclusão.

$$p \land q \land r \implies t$$

Todas as afirmações anteriores à conclusão são chamadas de premissas.

A conclusão só é verdadeira se todas as premissas forem verdadeiras.

Usa-se $\therefore$ entre as premissas e a conclusão.

**Exemplo:**
(p) Se Nina é um ser humano, então
(q) Nina é mortal.
Nina é um ser humano
$\therefore$ Nina é mortal.

| $p$ | $q$ | $p \implies q$ |
| :-: | :-: | :------------: |
|  V  |  V  |       V        |
|  V  |  F  |       F        |
|  F  |  V  |       V        |
|  F  |  F  |       V        |

A linha crítica da tabela verdade é a linha na qual todas as premissas possuem valores verdadeiros (nesse caso, a primeira).

O argumento só será válido se todas as linhas críticas tiverem suas conclusões verdadeiras.

**Exemplo 2:**

$p \lor (q \lor r)$
$\lnot r$
$\therefore p \lor q$

| $p$ | $q$ | $r$ | $q \lor r$ | $p \lor (q \lor r)$ | $\lnot r$ | $p \lor q$ |
| :-: | :-: | :-: | :--------: | :-----------------: | :-------: | :--------: |
|  V  |  V  |  V  |     V      |          V          |     F     |     V      |
|  V  |  V  |  F  |     V      |          V          |     V     |     V      |
|  V  |  F  |  V  |     V      |          V          |     F     |     V      |
|  V  |  F  |  F  |     F      |          V          |     V     |     V      |
|  F  |  V  |  V  |     V      |          V          |     F     |     V      |
|  F  |  V  |  F  |     V      |          V          |     V     |     V      |
|  F  |  F  |  V  |     V      |          V          |     F     |     F      |
|  F  |  F  |  F  |     F      |          F          |     V     |     F      |

Nesse exemplo, a quinta ($p \lor (q \lor r)$) e sexta ($\lnot r$) coluna são premissas e a última ($p \lor q$) é a conclusão.

Como, para ser um argumento verdadeiro, as linhas críticas devem ter uma conclusão verdadeira e isso é satisfeito no exemplo, o argumento é **válido**.
