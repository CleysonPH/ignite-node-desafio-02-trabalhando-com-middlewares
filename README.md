# Ignite: Desafio 02 - Trabalhando com middlewares

![Cover](.github/cover-node.js.png)

## Sobre o desafio

Nesse desafio você irá trabalhar mais a fundo com middlewares no Express. Dessa forma você será capaz de fixar mais ainda os conhecimentos obtidos até agora.

Para facilitar um pouco mais do conhecimento da regra de negócio, você irá trabalhar com a mesma aplicação do desafio anterior: uma aplicação para gerenciar tarefas (ou _todos_) mas com algumas mudanças.

Será permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo _todo_;
- Listar todos os _todos_;
- Alterar o `title` e `deadline` de um _todo_ existente;
- Marcar um _todo_ como feito;
- Excluir um _todo_;

Tudo isso para cada usuário em específico. Além disso, dessa vez teremos um plano grátis onde o usuário só pode criar até dez _todos_ e um plano Pro que irá permitir criar _todos_ ilimitados, isso tudo usando middlewares para fazer as validações necessárias.

## Como executar o projeto

1. Clone o repositório

```bash
git clone git@github.com:CleysonPH/ignite-node-desafio-02-trabalhando-com-middlewares.git
```

2. Instale as dependências

```bash
yarn
# ou
npm install
```

3. Execute a aplicação

```bash
yarn dev
# ou
npm run dev
```

## Como executar os testes

```bash
yarn test
# ou
npm run test
```
