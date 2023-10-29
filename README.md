# Upload AI - BackEnd

## 1 - Sobre

Aplicação que possibilita realizar upload de videos e por meio de IA, criar automaticamente títulos chamativos e descrições com um boa indexação.

## 2 - Tecnologias

Um pouco das tecnologias que foram utilizadas no projeto:

- NodeJS
- TypeScript
- Fastify
- Prisma
- SQLite
- Open AI
- Zod
- Tsx

## 3 - Instalação e uso

Você precisa ter o [Node](https://nodejs.org/en/), o [Git](https://git-scm.com/) e algum gerenciador de pacotes([NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm/) | [Yarn](https://classic.yarnpkg.com/lang/en/docs/install)) instalados em sua máquina.

```bash
1. Clone o repositório:
$ git clone https://github.com/felipems1/upload-ai-backend.git

2. Acesse a pasta e instale as dependências via terminal:
$ yarn install / npm install

3. Em seguida, crie um arquivo .env, copiando o formato do arquivo .env.example:
$ env.example -> .env

4. Execute as migrations com o comando:
$ yarn prisma migrate dev / npx prisma migrate dev

5. Inicie a aplicação em modo de desenvolvimento:
$ yarn dev / npm run dev

6. O servidor será aberto em http://localhost:3333
```

<p align="center">Projeto feito com ❤️ por <a href="https://www.linkedin.com/in/felipems12/">Felipe Moises</a></p>