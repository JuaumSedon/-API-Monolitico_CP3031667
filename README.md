# API REST para Gerenciamento de Usuários

Esta é uma API REST monolítica para gerenciamento de usuários desenvolvida para uma atividade prática.

## Tecnologias Utilizadas
- Node.js
- Express
- SQLite3

## Como Executar o Projeto

1. Certifique-se de ter o Node.js instalado no seu computador.
2. Abra o terminal na pasta raiz do projeto (`api-usuarios`).
3. Instale as dependências executando o comando:
   npm install

4. Inicie o servidor com o comando:
   node src/app.js

5. A aplicação estará rodando no endereço:
   http://localhost:3000

O banco de dados `database.sqlite` será gerado automaticamente na raiz do projeto ao rodar o servidor pela primeira vez.

## Endpoints Disponíveis

- **POST /users** : Cria um novo usuário (Requer JSON com `nome` e `email`).
- **GET /users** : Lista todos os usuários cadastrados.
- **GET /users/:id** : Busca um usuário específico pelo ID.
- **PUT /users/:id** : Atualiza o `nome` e `status` de um usuário.
- **DELETE /users/:id** : Altera o status do usuário para "inativo".
