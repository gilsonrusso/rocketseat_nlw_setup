# Backend

## Dependencies to Install

- npm i fastify
- npm i @fastify/cors
- npm i prisma -D
- npm i @prisma/client


## Init Db com Prisma/sqlite
#### Pq sqlite cria um banco de dados local sem precisarmos de docker entre outros.

### Criando o esquema basico da banco
- npx prisma init --datasource-provider SQLite

### Rodando a migration
- npx prisma migrate dev

### Abrindo o prisma Studio
- npx prisma studio
