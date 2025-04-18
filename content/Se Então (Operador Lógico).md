---
title: "Se Então (Operador Lógico)"
aliases:
  - se então
  - condicional
tags:
  - lógica
---

# Se Então

O operador lógico se então (ou condicional) define que a [[Proposição|proposição]] será falsa somente se a premissa for verdadeira e a conclusão falsa.

É equivalente a $\lnot p \lor q$.

| $p$ | $q$ | $p \implies q$ | $q \implies p$ (oposta) | $\lnot p \implies \lnot q$ (inversa) | $\lnot q \implies \lnot p$ (contrapositiva) |
| :-: | :-: | :------------: | :---------------------: | :----------------------------------: | :-----------------------------------------: |
|  V  |  V  |       V        |            V            |                  V                   |                      V                      |
|  V  |  F  |       F        |            V            |                  V                   |                      F                      |
|  F  |  V  |       V        |            F            |                  F                   |                      V                      |
|  F  |  F  |       V        |            V            |                  V                   |                      V                      |
