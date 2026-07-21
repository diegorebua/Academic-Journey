# Nível 8: Especialista Inicial (Conteinerização com Docker e Docker Compose)

Neste nível você empacotará toda a sua aplicação web e infraestrutura de banco de dados em containers isolados e reproduzíveis.

---

### Exercício 8.1: Dockerfile Otimizado (Multi-stage Build)
**Objetivo:** Criar um `Dockerfile` para uma aplicação Node.js utilizando *multi-stage build* (estágio de `builder` para compilar TypeScript/dependências de dev e estágio final ultra-leve com `node:alpine` prod-only).

---

### Exercício 8.2: Docker Compose Multi-serviços
**Objetivo:** Criar um arquivo `docker-compose.yml` que orquestre:
1. `api`: Container da sua aplicação Node.js.
2. `database`: Container PostgreSQL com volume persistente para manter dados salvos no host.
3. `redis`: Container Redis para cache.
- Garantir que a API só inicie após o PostgreSQL estar pronto (Healthcheck / `depends_on`).

---

### Exercício 8.3: Scripts de Migração Automática na Inicialização
**Objetivo:** Configurar um script de entrada (`entrypoint.sh`) no container que execute automaticamente as migrações do banco de dados (ex: `npx typeorm migration:run` ou `npx prisma migrate deploy`) antes de iniciar o servidor da API.
