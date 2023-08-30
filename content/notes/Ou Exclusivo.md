---
title: "Ou Exclusivo"
aliases:
- XOR
tags:
- lógica
---
# Ou Exclusivo

O Ou Exclusivo somente tem valor verdadeiro quando somente uma das proposições é verdadeira.

$$p \oplus q \equiv (\lnot p \land q) \lor (p \land \lnot q)$$

| $p$ | $q$ | $p \oplus q$ |
|:---:|:---:|:---:|
|  V  |  V  |  F  |
|  V  |  F  |  V  |
|  F  |  V  |  V  |
|  F  |  F  |  F  |