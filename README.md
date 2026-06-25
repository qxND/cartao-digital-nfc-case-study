# Cartão Digital NFC — Case Study

> Estudo de caso de uma aplicação web para cartão digital dinâmico, desenvolvida em contexto profissional.
> O código-fonte original não está disponível publicamente por questões de confidencialidade e propriedade intelectual.

<p align="center">
  <img src="./assets/demo.gif" alt="Demonstração do Cartão Digital NFC" width="800" />
</p>

## Visão Geral

O **Cartão Digital NFC** é uma aplicação web criada para apresentar perfis digitais de forma dinâmica, responsiva e visualmente personalizada.

A proposta era permitir que um cartão físico com NFC direcionasse o usuário para uma página online com informações de contato, bio, links sociais e identidade visual customizada.

Nesta versão de apresentação, o perfil demonstrativo utiliza o personagem **Pixel**, um gato fictício com estética tech, criado apenas para fins de portfólio e demonstração visual.

## Objetivo do Projeto

Criar uma experiência simples, rápida e acessível para substituir ou complementar cartões de visita tradicionais, conectando o mundo físico ao digital por meio de NFC e web.

## Funcionalidades

* Página dinâmica por usuário
* Perfil com nome, cargo, empresa, bio e avatar
* Links sociais interativos
* Interface responsiva
* Alternância visual de tema/cor
* Dados carregados a partir de banco PostgreSQL
* Estrutura preparada para múltiplos perfis digitais

## Stack Utilizada

* Python
* Flask
* PostgreSQL
* HTML
* CSS
* JavaScript
* Jinja Templates
* Linux / Deploy web

## Minha Participação

Atuei no desenvolvimento da aplicação web, estruturação das rotas, integração com banco de dados, renderização dinâmica dos perfis e organização da interface.

Também participei da configuração do ambiente de execução e validação do fluxo entre cartão NFC, página web e dados do perfil.

## Decisões Técnicas

A aplicação foi estruturada com Flask para manter o backend simples, direto e fácil de publicar em ambiente web.

Os dados dos usuários foram armazenados em PostgreSQL, permitindo que diferentes perfis fossem carregados dinamicamente a partir de um identificador na URL.

A interface foi construída com foco em impacto visual, responsividade e acesso rápido aos links principais.

## Demonstração

A demo abaixo mostra a aplicação em funcionamento, incluindo a troca de tema visual pela interface.

[Ver vídeo da demonstração](./assets/demo.mp4)

## Aprendizados

Este projeto reforçou minha experiência com desenvolvimento backend, aplicações web dinâmicas, integração com banco de dados, organização de assets estáticos e construção de interfaces voltadas para uso real.

Também foi um exercício importante de produto: transformar uma necessidade simples, compartilhar contato profissional, em uma experiência digital mais visual, memorável e personalizável.

## Nota de Confidencialidade

Este repositório apresenta apenas um estudo de caso sanitizado.
O código-fonte original não é público porque foi desenvolvido em contexto profissional e pode conter detalhes de implementação, marca ou informações pertencentes à empresa.

Nenhum dado sensível, credencial, informação interna ou código proprietário está incluído neste repositório.
