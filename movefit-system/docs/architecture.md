# Documento de Arquitetura Inicial

## Objetivo
Definir uma base de organização para o desenvolvimento do sistema Movefit com frontend e backend desacoplados.

## Visão de alto nível

- O **frontend** é um projeto independente, com ciclo de build/deploy próprio.
- O **backend** é um projeto independente, exposto via API HTTP.
- A integração entre ambos ocorre por uma **API REST**.

## Diretrizes de arquitetura

1. **Separação de responsabilidades**
   - Frontend: apresentação, experiência do usuário e estado da interface.
   - Backend: domínio, regras de negócio, persistência e segurança.

2. **API-first**
   - Contratos de API definidos antes da implementação de telas críticas.
   - Endpoints versionados (exemplo: `/api/v1`).

3. **Escalabilidade da base**
   - Estrutura preparada para evolução em módulos (catálogo, pedidos, auth, admin).

## Estrutura inicial

```text
/movefit-system
  /docs
    architecture.md
  /frontend
  /backend
  README.md
```
