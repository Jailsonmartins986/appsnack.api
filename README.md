# AppSnack API

API REST do **AppSnack** - plataforma de pedidos de lanches corporativos (Projeto Integrador I, UESPI - 2026.1, grupo Orquestrador).

## Tecnologias
Node.js 20+ - Express 4 - Sequelize 6 - MySQL 8 - JWT - bcrypt - Zod - Jest/Supertest

## Como executar
```bash
npm install
cp .env.example .env        # edite DB_PASS e JWT_SECRET
# crie o banco:  CREATE DATABASE appsnack CHARACTER SET utf8mb4;
npm run seed                # (opcional) popula dados de demonstração
npm run dev                 # http://localhost:3333
npm test                    # testes automatizados (usa SQLite em memória)
```

## Logins de demonstração (senha `123456`)
`ricardo@appsnack.com` (funcionário) - `cida@appsnack.com` e `fit@appsnack.com` (fornecedores) - `admin@appsnack.com`

## Endpoints
Veja `requests.http` (VS Code + extensão REST Client) com todos os exemplos.
