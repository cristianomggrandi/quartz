---
title: "História da Computação"
tags:
- informática
- software
- hardware
---
# História da Computação

Data: 06/08/2023

## Primórdios

O primeiro [[notes/Computador|computador]] digital eletrônico de grande escala foi o ENIAC (Electronic Numerical Integrator and Computer). Ele foi criado durante a Segunda Guerra Mundial para realizar cálculos envolvendo trajetórias táticas mais rapidamente que seria possível para os humanos. Inicialmente, os programas eram escritos com cartões perfurados manualmente. Ele foi utilizado por 10 anos, até 1955. Neste ano, um computador pesava 3 toneladas e consumia 50 [kW](https://pt.wikipedia.org/wiki/Watt "Watt") de potência, tendo um custo de US$ 200 000,00. Uma máquina destas podia realizar 50 multiplicações por segundo.

![ENIAC|300](notes/Imagens/eniac.jpg)

## Assembly

Para tornar o desenvolvimento mais rápido e simples, foi criada a linguagem Assembly, uma linguagem de baixo nível que, por meio de um assembler, gera o código absoludo de máquina (Machine Code).

```asm {title="Baixo nível (Assembly)"}
loop:   add c, a, b
		add, i, 1
		bqn i, 10, loop
```

## Linguagens de Alto Nível

Se o objetivo é facilitar e simplificar o desenvolvimento de programas, o próximo passo seria criar linguagens que se assemelhem cada vez mais à linguagem humana. Para isso, foram criadas as linguagens de alto nível. Elas necessitam de um compilador para gerar um código equivalente em linguagem de baixo nível. 

```c {title="Alto nível (C)"}
for (int i = 0; i < 10; i++)
	c = a + b
```
