# Desafio Técnico Java - Projeto Autonomy Base

## Avisos antes de começar

* Leia com atenção este documento todo e tente seguir ao máximo as instruções.
* Crie um repositório no seu GitHub sem citar nada relacionado a TechSolutio.
* Faça seus commits no seu repositório.
* Envie o link do seu repositório para o email do recrutador responsável.
* Você poderá consultar o Google, Stackoverflow, ChatGPT ou algum projeto particular na sua máquina; Dê uma olhada nos Materiais úteis.
* Dê uma olhada em como será a entrevista.
* Fique à vontade para perguntar qualquer dúvida aos recrutadores.
* Fique tranquilo, respire, assim como você, também já passamos por essa etapa ;).

Boa sorte :)

## Sobre o ambiente da aplicação:

Obedeça os requisitos informados, siga-os criteriosamente.

Se optar por um framework tente evitar usar muito métodos mágicos ou atalhos já prontos. Sabemos que essas facilidades aumentam a produtividade no dia-a-dia mas aqui queremos ver o seu código e a sua forma de resolver problemas;

Valorizamos uma boa estrutura de containeres criada por você.

## No dia da entrevista técnica

Na data marcada pelo recrutador tenha sua aplicação rodando na sua máquina local para execução dos testes e para nos mostrar os pontos desenvolvidos e possíveis questionamentos.

Faremos um code review junto contigo como se você já fosse do nosso time ❤️, você poderá explicar o que você pensou, como arquitetou e como pode evoluir o projeto.

Não esqueça de enviar o seu projeto para o repositório informado no email ao recrutador.

## Avaliação
Apresente sua solução utilizando o framework conforme boas práticas.

Atente-se a cumprir a maioria dos requisitos, pois você pode cumprir-los parcialmente e durante a avaliação vamos bater um papo a respeito do que faltou.

### O que será avaliado e valorizamos ❤️
* Habilidades básicas de criação de projetos backend.
* Conhecimentos sobre REST Uso do Git.
* Capacidade analítica.
* Apresentação de código limpo e organizado Conhecimentos intermediários de construção de projetos manuteníveis.
* Aplicação e conhecimentos de SOLID.
* Identificação e aplicação de Design Patterns.
* Noções de funcionamento e uso de Cache.
* Conhecimentos sobre conceitos de containers (Docker, Podman etc).
* Documentação e descrição de funcionalidades e manuseio do projeto.
* Implementação e conhecimentos sobre testes de unidade e integração.
* Identificar e propor melhorias.
* Boas noções de bancos de dados relacionais.
* Aptidões para criar e manter aplicações de alta qualidade. • Aplicação de conhecimentos de observabilidade.
* Utlização de CI para rodar testes e análises estáticas.
* Conhecimentos sobre bancos de dados não-relacionais. • Aplicação de arquiteturas (CQRS, Event-sourcing, Microsserviços, Monolito modular).
* Uso e implementação de mensageria.
* Noções de escalabilidade.
* Boas habilidades na aplicação do conhecimento do negócio no software.
* Boas práticas de software dentro do framework escolhido.

### O que não será avaliado
* UX/UI.
* Uso de Bibliotecas CSS.

### O que será um Diferencial
* Uso de Docker.
* Uma cobertura de testes consistente.
* Uso de Design Patterns.
* Documentação.
* Proposta de melhoria na arquitetura.
* Ser consistente e saber argumentar suas escolhas.
* Apresentar soluções que domina.
* Modelagem de Dados.
* Manutenibilidade do Código.
* Tratamento de erros.
* Cuidado com itens de segurança.
* Arquitetura (estruturar o pensamento antes de escrever).
* Carinho em desacoplar componentes (outras camadas, service, repository).

## Objetivo do Desafio

Avaliar conhecimentos práticos em:

* Java com Spring Boot
* MySQL / PostgreSQL / Oracle e MongoDB
* Testes unitários
* Design Patterns
* Clean Code
* Git e CI/CD
* Redes e Integrações via API REST
* Frontend com Angular

## Desafio

Criar uma aplicação web de monitoramento de dispositivos conectados à rede.

### Funcionalidades

* Cadastro de dispositivos com nome, IP e status (ativo/inativo)
* Histórico de status salvo no Banco de Dados de sua escolha
* Consulta dos últimos 10 status por dispositivo
* Painel de visualização dos dispositivos em tempo real (simulado)

### Requisitos Técnicos - Backend

* Java 17+ com Spring Boot
* Banco relacional (MySQL) para cadastro de dispositivos
* MongoDB para histórico de status
* Agendador de verificação de status de IPs (simulado com ping)
* Testes unitários com JUnit
* Padrões de projeto aplicados (Builder, Strategy, etc.)
* API RESTful bem definida

### Requisitos Técnicos - Frontend

* Angular 15+ ou 20
* Visualização dos dispositivos com status atual
* Histórico em gráfico ou tabela simples
* Componente de busca e filtro por nome ou IP
* Consumo da API REST

### DevOps

* Dockerfile para backend e frontend
* Docker Compose com MySQL, MongoDB, backend e frontend

## Entrega

* Tempo estimado será informado na entrevista preliminar.
* Criar um repositório público no GitHub
* Instruções no README para execução local

### Enviar link ao recrutador

* Seu Nome
* Nome do recrutador
* Link do repositório
* Link do Linkedin

## Materiais Úteis
* https://www.techsolutio.com
* https://www.devmedia.com.br/rest-tutorial/28912
* https://martinfowler.com/articles/microservices.html
* https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing
* https://refactoring.guru

Boa sorte! 🍀
