# Nível 3: Intermediário Inicial (Servidor HTTP e CRUD em Memória)

Neste nível você construirá sua primeira API RESTful utilizando Express.js ou Fastify com rotas CRUD mantendo o estado em memória.

---

### Exercício 3.1: Endpoint de Status (Healthcheck)
**Objetivo:** Criar um servidor Express com a rota `GET /healthcheck` que responda com o status `200 OK`, horário atual do servidor (`uptime` e `timestamp`) e versão da aplicação.

---

### Exercício 3.2: CRUD Completo de Produtos (Em Memória)
**Objetivo:** Criar uma API REST contendo as seguintes rotas para a entidade `Produto` (`id`, `nome`, `preco`, `estoque`):
- `GET /produtos` - Lista todos os produtos.
- `GET /produtos/:id` - Retorna um produto específico (ou 404 se não existir).
- `POST /produtos` - Cria um novo produto (gerando ID único).
- `PUT /produtos/:id` - Atualiza um produto existente.
- `DELETE /produtos/:id` - Remove um produto.

---

### Exercício 3.3: Middleware de Validação
**Objetivo:** Criar um middleware Express `validarProdutoBody` que garanta que no `POST /produtos` os campos `nome` (string não vazia) e `preco` (número positivo) estejam presentes no `req.body`. Caso contrário, retorne status `400 Bad Request` com mensagem detalhada do erro.
