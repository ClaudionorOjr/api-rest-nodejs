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
- [x] Deve ser possível identificarmos o usuário entre as requisições;
- [x] O usuário só pode visualizar transações o qual ele criou;

### RNF

> O que vai utilizar para atingir cada uma das funcionalidades
