
# Saúde em Casa

Sistema web para organização e gerenciamento de atendimentos domiciliares realizados por profissionais da saúde.

## Sobre o Projeto

O Saúde em Casa é uma aplicação desenvolvida para facilitar o controle de tarefas e atendimentos realizados por profissionais de saúde em domicílio.

### O sistema permite:

👩‍⚕️ Cadastro de profissionais

📋 Criação e gerenciamento de tarefas

🔐 Controle de acesso por tipo de usuário (Admin e Profissional)

📊 Painel administrativo para gestão completa

### Tecnologias Utilizadas

Next.js (App Router)

Supabase (Banco de Dados)

Autenticação manual com hash de senha

Middleware para proteção de rotas

Tailwind CSS para estilização

### Tipos de Usuário
🔹 Admin

Acessa o painel administrativo

Cadastra profissionais

Cria e gerencia tarefas

🔹 Profissional

Realiza login no sistema

Visualiza apenas as tarefas atribuídas a ele

### 🔐 Segurança

Autenticação baseada em cookies

Proteção de rotas via middleware.js

Senhas armazenadas com hash

Controle de acesso por tipo de usuário

### Objetivo do Projeto

Organizar e centralizar o gerenciamento de atendimentos domiciliares, trazendo mais controle, segurança e praticidade para equipes da área da saúde.


This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
