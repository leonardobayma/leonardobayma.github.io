---
title: 'Entendendo o delta time em Game Engines '
description: 'Explicando a lógica do delta time no contexto de desenvolvimento de jogos'
pubDate: 'Aug 23 2026'
heroImage: '../../assets/blog-placeholder-1.jpg'
---
Estou voltando a desenvolver jogos com mais consistência, e dessa vez parei de enrolar e fui atrás de entender algum dos passos automáticos em tutoriais, o o primeiro deles é o uso do delta time.

E no fim não passa de uma simples aplicação da regra de três, basicamente o que o delta time faz é tirar a lógica de aplicar um valor por frame para aplicar um valor por segundo, simples assim, pelo menos em objetos que não exigem cálculos de física,
o tempo deslocado que é contabilizado é a diferença entre o frame atual e o último frame, isso em segundos (s), assim caso não importe quantos frames o seu computador rode, ele só vai aplicar o valor proporcional a parcela de tempo contabilizada,

