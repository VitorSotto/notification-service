# notification-service

Microsserviço de notificação desenvolvido no evento IgniteLab da [@rocketseat](https://github.com/rocketseat).
## Como foi feito?

Utilizando o **TypeScript** e o framework **NestJS**, com a ORM **Prisma** e um banco de dados **SQLite** apenas para exemplificação de banco, mas facilmente podesse utilizar outro banco como por exemplo PostgreSQL ou MySQL.

Configurado os teste dos casos de usos necessários com **Jest** e testados corretamente.



## Funcionalidades

- Envio de notificações.
- Cancelamento de notificações.
- Receber quantidade de todas as notificações por `recipient`.
- Receber todas as notificações por `recipient`.


## Aprendizados

Com este projeto pude aprender melhor sobre o **Nest** e **TypeScript**. Descobri `patterns` importantes como `repository patterns` e `data mapper`, `getters` e `setters` e também a sobre testes unitário com o **Jest** e sua importância em um projeto. A questão de **tratamento de erros** dentro de um projeto também foi feita. Dentro do **Nest** foi aprendido a **inversão de dependência** e **injeção de dependência**.


## Instalação

Para instalar as dependências do projeto, rode o seguinte comando:

```bash
  yarn install
```
    
## Rodando os testes

Para rodar os testes, rode o seguinte comando:

```bash
  yarn test
```


## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env

`DATABASE_URL`


## Rodando em desenvolvimento

Para rodar o como desenvolvimento, rode o seguinte comando:

```bash
  yarn start:dev
```


## Autores

- [@vitorsotto](https://www.github.com/vitorsotto)

