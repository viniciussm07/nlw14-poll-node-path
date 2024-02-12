# Backend aplicação de enquete

Programa desenvolvido na 14ª NLW (Next Level Week).

Tecnologias utilizadas:
- Node.js
- Typescript
- Docker
- PostgreSQL
- Redis

## Pré-requisitos

- Node 20^
- npm 9^
- Docker 25^


## Quick start

Após clonar o repositório suba duas imagens docker por meio do docker compose:
```bash
docker compose up -d
```

Instale os devidos pacotes:
```bash
npm i
# or
yarn install
# or
pnpm install
```

Rode o projeto:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

O projeto deve estar rodando na porta 3333

Para testar os endpoints encontrados na pasta `/source/http/routes` abra o cliente http de sua preferência em [http://localhost:3333](http://localhost:3333) e faça as requisições desejadas
