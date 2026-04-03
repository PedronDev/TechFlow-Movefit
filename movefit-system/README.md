# Movefit System

Estrutura inicial do repositório para o sistema Movefit, com separação clara entre frontend e backend.

## Arquitetura inicial

- **Frontend (`/frontend`)**
  - Aplicação cliente (web) responsável pela interface do usuário.
  - Consome os dados do backend via API.

- **Backend (`/backend`)**
  - API e regras de negócio.
  - Responsável por autenticação, catálogo, pedidos, estoque e área administrativa.

- **Comunicação entre camadas**
  - **API REST** como padrão inicial de integração entre frontend e backend.
  - Formato de troca de dados: **JSON**.

## Estrutura de pastas

```text
/movefit-system
  /docs
  /frontend
  /backend
  README.md
```
Stacks
 FRONTEND
 - HTML, CSS, JS (inicial)
 - Depois: React + Vite
 BACKEND
 - Node.js + Express
 BANCO
 - PostgreSQL
