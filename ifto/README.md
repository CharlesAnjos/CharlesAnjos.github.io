# Projetos na IFTO

Esta é uma lista de projetos desenvolvidos durante o curso de Sistemas Para Internet do Instituto Federal de Educação, Ciência e Tecnnologia do Tocantins.

## [Sistema de Inscrição de Projetos Acadêmicos (SIPA) - Backend](https://github.com/CharlesAnjos/SIPA-Backend)

Tecnologias e Ferramentas utilizadas: nodejs, mongodb, expressjs, mongoose, rest api

Este projeto consiste em um servidor com uma API Restful para gerenciamento de Projetos Acadêmicos. Administradores do sistema podem criar prêmios, autores para envio de projetos e avaliadores para avaliar projetos de um determinado prêmio.

## [Sistema de Inscrição de Projetos Acadêmicos (SIPA) - Frontend](https://github.com/CharlesAnjos/SIPA-Frontend)

Tecnologias e Ferramentas utilizadas: Flutter

Este projeto consiste em um aplicativo móvel feito em Flutter que acessa a API disponibilizada pelo projeto [Sistema de Inscrição de Projetos Acadêmicos (SIPA) - Backend](https://github.com/CharlesAnjos/SIPA-Backend). Através desse aplicativom, administradores do sistema podem criar prêmios, autores para envio de projetos e avaliadores para avaliar projetos de um determinado prêmio.

## [Adivinhe o País - Jogo Android (Java)](https://github.com/CharlesAnjos/JogoPaisesAndroid)

Tecnologias e Ferramentas utilizadas: Android, Java, Text-to-Speech, Firebase, SQLite

Este projeto consiste em um aplicativo móvel para Android feito em Java, disponível no GitHub [aqui](https://github.com/CharlesAnjos/JogoPaisesAndroid) . Este aplicativo acessa uma API pública de informações sobre países. Feito o acesso, o aplicativo filtra as informações desejadas e salva ela em um banco interno SQLite. As informações salvas neste banco interno são usadas para criar uma partida de um jogo de adivinhação onde o jogador deve adivinhar o nome do país a partir da bandeira. O jogo tem gameplay narrado via Text-to-Speech. Ao final, o jogador visualiza sua pontuação (quantidade de acertos) e a pontuação é enviada para um servidor Firebase que serve de placar. O Gameplay do jogo é similar ao jogo educacional Kahoot, com cada partida do jogo sendo dividida em telas onde o jogador é apresentado com a bandeira do país a ser adivinhado, juntamente com 4 opções de nomes de países como escolhas.