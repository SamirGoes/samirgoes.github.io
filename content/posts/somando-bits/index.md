+++ 
draft = false
date = 2024-06-25T22:00:42-03:00
title = "Somando bits"
description = ""
slug = ""
authors = []
tags = ["calculadora"]
categories = []
externalLink = ""
series = []
+++

## Somando bits

Há alguns meses atrás, eu vi esse vídeo aqui:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/BbnDmeNojFA/0.jpg)](https://www.youtube.com/watch?v=BbnDmeNojFA)

Assisti superficialmente de início, mas é um BAITA conteúdo. Mas ai imaginei E SE: eu assistir devagar pra entender os conceitos e TALVEZ reproduzí-los.

Foi aí que começou minha saga anotando tudo num caderninho. Em especial a parte de simulação das portas lógicas, e novamente veio um E SE, eu recriar tudo isso eletronicamente? E SE eu criar o mesmo somador utilizando componentes eletrônicos dos quais eu tenho familiariedade ~~quase nula~~? Pô, deve ser legal, vamo entender.

Começou minha saga assistindo vídeos no youtube e revisitando textos que eu me baseei pra acender os primeiros leds no meu Arduino. Cheguei neles, **transistores**.
Mas CALMA LÁ PARSERO, não adianta sair queimando componente porque não colocou resistor sem antes testar essa bagaça nas sketchs da vida.

Fui eu fuçar e fazer skechts, que funcionavam as vezes. Foi lá que eu descobri que existem os CI's (circuitos integrados) de portas lógicas que facilitavam pra caramba.

Levantei tudo que poderia precisar e graças a shopee, consegui comprar tudo por valores nem tão acessíveis e agradáveis a um mero curioso.

Mas CALMA LÁ DENOVO MEUAMIGO, vamos tentar fazer tudo isso usando python, já que é uma linguagem que eu também não sou muito familiarizado.

**Aparentemente eu gosto de arrumar problemas.**

Foi ai que surgiu a ideia de:

- Reproduzir a parte das portas lógicas e do somador com python;
- FAZER TUDO ELETRÔNICO COM LEDS, TRANSISTORES, BOTÕES E MUITOS JUMPERS;

Mas nessa primeira parte vamos focar no python, até pra entender os conceitos que serão aplicados.

VEJO VOCÊS LOGO