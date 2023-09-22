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

### Requisitos:

- [NodeJS](https://nodejs.org/en/)
- [Npm](https://www.npmjs.com) ou [yarn](https://yarnpkg.com)

Clone o projeto em sua máquina e instale as dependências com o comando:

```shell
yarn ou npm install
```

Em seguida, crie um arquivo **.env**, copiando o formato do arquivo **.env.example**:

```
env.example -> .env
```


Execute as migrations com o comando:

```
yarn prisma migrate dev

ou

npx prisma migrate dev
```

Para rodar o servidor localmente:

```
yarn dev

ou

npm run dev
```

---

#### As requisições podem ser testadas em programas como o [Insomnia](https://insomnia.rest/download), [Postman](https://www.postman.com), etc!

---

## 4 - Endpoints

| Método | Rota                  | Descrição                                            |
| ------ | --------------------- | ------------------------------------                 |
| GET    | /prompts              | get-prompt                                           |
| POST   | /videos               | upload-video                                         | 
| POST   | /videos/${videoId}/transcription    |     create-transcription               |
| POST   | /ai/complete          | generate-ai-completion                               | 