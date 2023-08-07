---
title: "Software"
alias: Softwares
tags:
- informática
- software
---
# Software

Data: 06/08/2023

Softwares são programas que contém um conjunto de instruções que operam o hardware do [[notes/Computador|computador]]. Por exemplo, é assim que 3 instruções dadas a um computador com processador baseado em 32 [[notes/Bit|bits]] se parecem:

	0100 0010 0011 0101 0101 0100 0011 0110
	0100 1110 1100 1100 1001 0110 0110 1000
	0000 0101 1111 1110 1101 0011 0000 1100

Para poder realizar as instruções presentes no programa, o ambiente computacional é organizado como uma hierarquia de funções, onde cada uma é responsável por uma tarefa específica:

- Programas de Aplicação
- Compiladores
- [[notes/Sistema Operacional|Sistema operacional]]
- [[notes/Hardware|Hardware]]

Existem alguns tipos de Software:

- [[notes/App|Programa de Aplicação (App)]]

Para escrever um software, é possível escrever diretamente o código binário, mas uma maneira mais simples é escrever usando uma linguagem de alto nível (linguagem mais próxima da humana) e utilizar um compilador para traduzir o código dessa linguagem para seu equivalente em uma linguagem de baixo nível (geralemente Assembly ou binário), que o [[notes/Hardware|hardware]] consegue entender.

```c {title="Alto nível ([[notes/C|C]])"}
for (int i = 0; i < 10; i++)
	c = a + b
```
```asm {title="Baixo nível (Assembly)"}
loop:   add c, a, b
		add, i, 1
		bqn i, 10, loop
```

