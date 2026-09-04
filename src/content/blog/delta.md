---
title: 'Entendendo o delta time em Game Engines '
description: 'Explicando a lôgica do delta time no contexto de desenvolvimento de jogos'
pubDate: 'Aug 23 2026'
heroImage: '../../assets/blog-placeholder-1.jpg'
---
Estou voltando a desenvolver jogos com mais consistencia, e dessa vez parei de enrolar e fui atrás de entender algum dos passso automaticos em turoriaais, o e o primeiro deles é o uso do delta time.

E no fim não passa de uma simples aplicaçao da regra de tres, basicamente o que o delta time faz. é tirar a logica de aplicar um valor por frame, para aplicar um valor por segundo, simples assim, pelo menos em objetos que nao exigem calculos de fisica,
o tempo deslocado que é contqabilizado é a diferenaçá entre o frame atual e o ultimo frame, isso em segundos (s), assim caso nao importante quantos frames o seu computador rode, ele so vai aplicar o valor proporcional a parcela de tempo contabilizada,

