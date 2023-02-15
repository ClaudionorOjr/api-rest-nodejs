# Criando API RESTful com Node.js

## Tecnologias 🔧

- dotenv

- ESLint

  - Lint: padronização de código
  - `npm i eslint -D`

- Fastify

  - Suporte nativo para o TypeScript
  - `npm i @fastify/cookie` // Trabalhar com cookies no fastify

- Supertest

  - Permite realizar requisições para a aplicação sem que esteja no ar
  - `npm i supertest -D`

- TypeScript

- tsx

  - `npm i @types/node -D`

- tsup

  - `npm i tsup -D`

- Vitest

  - `npm i vitest -D`

- Zod

### Comandos:

`npx knex -h` // Comando de ajuda Knex  
`npx knex migrate:make *namemigrate*` // Criação de migrate em Knex  
`npm run knex -- migrate:latest` // Execução de todas as migrations  
`npm run knex -- migrate:rollback` // Desfazer a migration executada

---

### RF

- [x] O usuário deve poder criar uma nova transação;
- [x] O usuário deve poder obter um resumo da sua conta;
- [x] O usuário deve poder listar todas as transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação única;

### RN

- [x] A transação pode ser do tipo crédito que somará ao valor total ou débito que subtrairá;
- [ ] Deve ser possível identificarmos o usuário entre as requisições;
- [ ] O usuário só pode visualizar transações o qual ele criou;

### RNF

> O que vai utilizar para atingir cada uma das funcionalidades

---

#### Anotações:

Streams?  
Mecanismos para ler e escrever dados de forma assíncrona, controlada e em partes.  
Método .pipe?  
Encaminha os dados provindos de uma stream para outra.  
Chunks em Streams no Node.js?  
Pedaços de dados que são lidos e escritos em uma stream de forma assíncrona.  
O que é uma "interface" em TypeScript?  
Um conjunto de tipos que especificam as propriedade e métodos que um objeto deve ter.  
Cookies?  
Formas de manter contexto entre requisições.
Testes unitários?  
São testes que validam o comportamento de uma única unidade de código, como uma função ou método. Eles são úteis para garantir que cada parte da aplicação esteja funcionando corretamente, sem depender de outras partes.
Testes de integração?  
São testes que validam a integração entre várias partes da aplicação, como a integração entre a camada de banco de dados e a camada de serviço. Eles são importantes para garantir que a aplicação esteja funcionando corretamente como um todo.
Testes e2e (end-to-end)?  
São testes que validam o comportamento da aplicação como um todo, simulando a interação do usuário com a aplicação. Eles são importantes para garantir que a aplicação esteja funcionando corretamente em todos os níveis, desde a camada de interface até a camada de banco de dados.
