---
layout: post
title:  "Back to Back! - Part III"
date:   2017-05-01
categories: Javascript, Vuejs
---


![Vuejs](https://github.com/IgorVieira/igorvieira.github.io/blob/master/_images/vuejs.jpg?raw=true)


Antes de mais nada eu tenho que pedir desculpa a vocês, estava em um processo de saída de uma empresa, e com um monte de teste e vários trabalhos que estava fazendo, organizar tudo estava complicado, estressante e no fim eu passei mal para caramba, uma bruta enchaqueca, que me levou ao hospital, na verdade, eu nem deveria está escrevendo esse post, meu médico me proibiu, mas... eu queria continuar o nosso projeto com Vuejs, eu acho incrível, fácil e prático, a única coisa que eu estou achando complicado é a parte de testes unitários, entretanto eu vou continuar com nosso app.


Mas, antes, eu quero falar sobre o nosso server, o back da nossa aplicação, daqui em diante, vai ser necessário termos um server, para poder disponibilizar os nosso serviços, e vamos modificar um pouco a nossa aplicação para poder utilizar de fato os serviços vindos da nossa API, e ao fim, e provavelmente, vamos testar a nossa API, é que no primeiro principio, conseguimos de fato testar a parte do nosso front com testes e2e, válidos, quero voltar aos teste unitários no front, que acho muito válido, entretanto, mesmo quando estamos desenvolvendo, temos que ter a sabedoria e entender que existem outras atividade que precisam ser feitas, e nesse caso isso é o nosso server, e vamos ao código.


Nossa estrutura, teremos que montar um certo setup, vamos criar um novo folder para a nossa aplicação, vamos mandar um mkdir ```tasks-server```

Em seguida vamos digitar o seguinte:

```
  sudo npm init -y

```
Ele já vai criar o nosso package.json, o nosso gerenciador de pacotes nodejs, vamos baixar alguns pacotes para o nosso server, entre eles estão o Express, Consig, Mongoose e outros como Mocha e Chai, 

