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

## Próximos passos sugeridos

1. Definir stack do frontend (ex.: React + Vite/Next.js).
2. Definir stack do backend (ex.: Node.js + Express/Nest).
3. Modelar recursos REST iniciais (produtos, usuários, pedidos, estoque).
4. Adicionar documentação técnica em `/docs`.
