# 👤 API de Cadastro de Usuários (MongoDB + Prisma)

API REST com Node.js, Express e Prisma usando MongoDB. Permite criar, listar, atualizar e deletar usuários.

## 🚀 Tecnologias
- Node.js + Express
- Prisma ORM
- MongoDB
- JavaScript (ESM)

## ⚙️ Como rodar

1. Instale as dependências:
```
npm install
```

2. Configure o `.env`:
```
DATABASE_URL="mongodb+srv://usuario:senha@cluster.mongodb.net/userdb"
```

3. Gere o cliente Prisma:
```
npx prisma generate
```

4. Inicie o servidor:
```
npm run dev
```

## 📬 Endpoints

- `POST /users` – Cria usuário
- `GET /users` – Lista usuários (com filtros opcionais)
- `PUT /users/:id` – Atualiza usuário
- `DELETE /users/:id` – Deleta usuário

## 📁 Estrutura

```
.
├── src/
│   └── server.js
├── prisma/
│   └── schema.prisma
├── .env.example
├── package.json
├── README.md
```
