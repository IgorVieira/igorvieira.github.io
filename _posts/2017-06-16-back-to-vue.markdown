---
layout: post
title:  "Back to Back! - Part III"
date:   2017-06-16
categories: Javascript, Vuejs
---


![back](https://github.com/IgorVieira/igorvieira.github.io/blob/master/_images/back-to-back.png?raw=true)


Antes de mais nada eu tenho que pedir desculpa a vocês, estava em um processo de saída de uma empresa, e com um monte de teste e vários trabalhos que estava fazendo, organizar tudo estava complicado, estressante na real, e no fim eu passei mal para caramba, uma bruta enchaqueca, que me levou ao hospital, passados alguns dias eu voltei, e fui direto trabalhar, mas... eu queria continuar o nosso projeto com Vuejs, eu acho incrível, fácil e prático, a única coisa que eu estou achando complicado é a parte de testes unitários, entretanto eu vou continuar com nosso app.

Nesse momento, eu quero somente trabalhar a parte com front-end, eu desenvolvi uma [API](https://github.com/IgorVieira/base-api) com tudo o que vamos precisar para desenvolver o restante da nossa aplicação no front, não é muito, mas  suficiente para podermos trabalhar, a única coisa que precisamos é organizar o que temos junto ao nosso servidor.


Vamos por passos, agora nessa primeria etapa, vamos precisar de duas bibliotecas para melhorar o restante da nossa aplicação, o `vue-router` e o `vue-resource`, primeiro o vue-resource, é o que precisamos para conectarmos as nossas requisições do back ao front e o inverso, `vue-router` será necessário quando formos para uma outra parte da nossa aplicação, ao que tem mais haver com a parte de edição das nossas tasks, vamos usar um pouco de bootstrap, para agilizar o processo, mas o foco é vue.