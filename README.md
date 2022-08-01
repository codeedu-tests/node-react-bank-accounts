## Descrição

O projeto consiste na criação de um sistema de transferência entre contas bancárias.

## Tecnologias e requisitos

* Back-end - Node.js com TypeScript (Pode ser usado qualquer lib ou framework)
* Front-end - React.js com TypeScript (Pode ser usado Create React App ou Next.js)
* Docker para orquestar o ambiente da aplicação

## Contexto do sistema

Os usuários de um banco acessarão uma página na WEB que mostrará o saldo de sua conta bancária e será possível fazer
transferências de valores entre as contas deste banco. As transferências deverão ser validadas, correntistas sem saldo
ou conta inválidas deverão ser informadas ao usuário no momento da transferência.

Os usuários também poderão ver o histórico de transações de sua conta bancária.

## Design do sistema

### Back-end - Node.js com TypeScript

Você deve criar uma API Rest que aceita realizar a listagem das transações, mostrar o saldo atual e fazer transferências entre as contas.
Esta aplicação deverá ser construída usando conceitos de Clean Architecture/Arquitetura Hexagonal e Domain Driven Design.

Criar a aplicação usando pirâmides de testes será muito bem vindo.

### Front-end - React.js

O front-end da aplicação deverá mostrar o saldo da conta bancária, permitir fazer transferências e listar o histórico das transações.

Fique a vontade para organizar páginas ou modais e até usar libs de estilização para React.js. A componetização e composição serão muito
bem-vindos.

Criar a aplicação usando pirâmides de testes será muito bem vindo.

## Docker

Crie as duas aplicações montando-as com Docker de forma que ao fazer `docker-compose up` seja possível testar todo o ambiente. 
O Docker deve levantar back-end, front-end, banco de dados e o RabbitMQ.

## Entrega

Subir a aplicação em um repositório Git remoto e disponibilizar o link.

