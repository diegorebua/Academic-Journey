# Nível 4: Intermediário (Banco de Dados, SQL e ORM)

Neste nível você conectará sua aplicação a um Banco de Dados Relacional (PostgreSQL) usando SQL puro e ORMs (TypeORM/Prisma).

---

### Exercício 4.1: Modelagem e Queries SQL Puras
**Objetivo:** Escrever scripts SQL para:
1. Criar as tabelas `usuarios` (`id`, `nome`, `email`, `criado_em`) e `pedidos` (`id`, `usuario_id`, `valor_total`, `status`, `criado_em`) com chave estrangeira.
2. Escrever uma consulta SQL com `JOIN` que traga todos os usuários e o valor total gasto por cada um em pedidos com status `'CONCLUIDO'`.

---

### Exercício 4.2: Integração com ORM (TypeORM ou Prisma)
**Objetivo:** Configurar o ORM para conectar ao PostgreSQL e definir as entidades `User` e `Post` (relacionamento 1 para N). Criar um Service que salve um novo post vinculado a um usuário existente.

---

### Exercício 4.3: Paginação e Filtros de Consulta
**Objetivo:** Implementar no endpoint `GET /usuarios` suporte a query params para paginação (`page`, `limit`) e busca por nome (`search`), garantindo que a consulta no banco use `LIMIT`, `OFFSET` e `LIKE`/`ILIKE` eficientemente.
