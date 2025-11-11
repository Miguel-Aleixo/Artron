# Artron

Sistema de Gestão de Manutenção Industrial

O **Artron** é um sistema desktop voltado para empresas que desejam organizar e acompanhar atividades de manutenção industrial.  
Ele permite registrar máquinas, planejamentos de manutenção preventiva, ordens de serviço corretivas e históricos completos de execução.

O foco é tornar o fluxo de manutenção mais **organizado, rastreável e eficiente**.

---

## 🚀 Tecnologias Utilizadas

| Camada | Tecnologia | Descrição |
|-------|------------|-----------|
| **Frontend (Desktop UI)** | **Electron + Angular** | Interface desktop com componentes Angular Material integrados ao ambiente local via Electron. |
| **Design de UI** | **Angular Material** | Biblioteca oficial de UI do Angular, adotada amplamente por empresas. |
| **Backend / API** | **NestJS** | Framework Node.js modular e escalável, ideal para aplicações corporativas. |
| **ORM / Acesso ao Banco** | **Prisma** | ORM moderno e tipado para comunicação segura e produtiva com o banco. |
| **Banco de Dados** | **PostgreSQL** | Banco relacional robusto, confiável e gratuito. |

---

## 🧩 Funcionalidades Principais (versão inicial)

- Cadastro de máquinas e equipamentos
- Registro de ordens de serviço (preventiva e corretiva)
- Controle de responsáveis / técnicos
- Histórico de manutenção executada
- Prioridade e status de cada ordem
- Dashboards com indicadores básicos

---

## 📂 Estrutura Geral do Projeto

artron/
├─ backend/ → API NestJS + Prisma
├─ frontend/ → Angular + Material
└─ desktop-shell/ → Electron integrando tudo

---

## 🛠️ Como Executar (quando o projeto estiver pronto)

```bash

### 1. Instale dependências
npm install

### 2. Configure o banco PostgreSQL
Crie um banco chamado:
artron_db

### 3. Gere o schema do Prisma
npx prisma migrate dev

### 4. Rode o backend
cd backend
npm run start:dev

### 5. Rode o frontend
cd frontend
ng serve

### 6. Inicie o app desktop
cd desktop-shell
npm start

```
---

## 🎯 Objetivo do Projeto

Este projeto foi criado com propósito de estudo e evolução profissional, explorando:
- Arquitetura limpa entre frontend, backend e camada de integração
- Desenvolvimento desktop moderno sem abandono do ecossistema web
- Tecnologias utilizadas amplamente em empresas de médio e grande porte

---

## 🧱 Status do Projeto
> Em desenvolvimento.

---

## 📝 Licença
Projeto livre para estudos e apresentação em portfólio.
