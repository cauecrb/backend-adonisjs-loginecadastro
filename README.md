# Backend Adonis, cadastro de usuario e produtos e login

Api desenvolvida com adonis que contem um sistema de login através de middleware e com token, utilizando PostgreSQL como banco de dados.

![](../cadastrousuarioinsomnia.png)

## Setup

para instalar a api e exutar, use o seguinte comando:

```bash
adonis new yardstick --api-only
```

ou clone o repo e instale manualmente com o seguinte comando:`npm install`.


### Migrations

rode o comando abaixo para efetuar as migrations no Banco de Dados

```js
adonis migration:run
```

## uso

Uma api que recebe cadastro de usuarios para login, e atravé do token é possivel cadastrar, deletar e consultar uma tabela de produtos e valores, seu funcionamento pode ser visualizado em uma ferramenta  que faz requisiçoes rest, Insomnia, Postman.

Cauê Rafael Burgardt
