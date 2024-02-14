# Sistema de Jogadores

## Stacks - Fullstack

``` by @VetVictor33 ```
## Instruções para rodar o projeto

### Docker

  * criar o aquivo `.env` na raiz do backend com a variável DATABASE_URL presente no arquivo `.env.example`;
  * `docker-compose up -d` para criar o container com o PostgreSQL

### Backend

  * `npm install` p/ instalar as dependências
  * `npx prisma migrate dev` para atualizar o schema do banco de dados com as migrations do Prisma
  * `npm run build && npm start` para buildar e iniciar o backend na porta 3333 do localhost
  * ou `npm run start:dev` para rodar em modo de desenvolvimento

### Frotend

  * `npm install` p/ instalar as dependências
  * `npm run build && npm start` para builda e rodar o projeto,
  * ou `npm run dev` para rodar em modo de desenvolvimento
