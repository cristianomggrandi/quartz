---
title: "Lógica"
aliases:
  - lógicas
tags:
  - lógica
  - matemática
---

# Lógica

Na [[Matemática|Matemática]], lógica é a subárea que explora aplicações da lógica formal na matemática.

## Conectivos Lógicos

|    Conectivo    |  Símbolo   |
| :-------------: | :--------: |
|        e        |  $\land$   |
|       ou        |   $\lor$   |
|  ou exclusivo   |  $\oplus$  |
|       não       |  $\lnot$   |
|    se então     | $\implies$ |
| se e somente se |   $\iff$   |

## Tabela Verdade

Tabela verdade é uma tabela que mostra o valor lógico de uma proposição.

**Exemplo:** Sendo $p$ e $q$ das proposições, a tabela verdade de $p \land (q \lor \lnot p)$ é:

| $p$ | $q$ | $q \lor p$ | $p \land q$ | $\lnot p$ | $\lnot q$ | $\lnot p \land \lnot q$ | $\lnot p \lor \lnot q$ |
| :-: | :-: | :--------: | :---------: | :-------: | :-------: | :---------------------: | :--------------------: |
|  V  |  V  |     V      |      V      |     F     |     F     |            F            |           F            |
|  V  |  F  |     V      |      V      |     F     |     V     |            F            |           V            |
|  F  |  V  |     V      |      F      |     V     |     F     |            F            |           V            |
|  F  |  F  |     F      |      F      |     V     |     V     |            V            |           V            |

## Lei de De Morgan

A Lei de De Morgan (ou Lei de Negação ou Inversão) define que:

$$
\lnot (p \lor q) \equiv \lnot p \land \lnot q
$$

$$
\lnot(p \land q) \equiv \lnot p \lor \lnot q
$$
