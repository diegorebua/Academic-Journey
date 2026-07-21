# Nível 6: Avançado Inicial (Upload de Arquivos, Security Hardening & Rate Limiting)

Neste nível você tratará entrada de arquivos multipart/form-data, regras de upload seguro e proteção da API contra abusos.

---

### Exercício 6.1: Upload de Arquivos com Multer
**Objetivo:** Configurar o `multer` para gerenciar o upload de imagens de avatar no endpoint `POST /usuarios/avatar` (com rota protegida por JWT).

---

### Exercício 6.2: Validação de Segurança em Uploads
**Objetivo:** Adicionar regras rígidas ao upload de avatar:
- Aceitar apenas extensões `.png`, `.jpg` ou `.jpeg` (validar MIME type).
- Limitar o tamanho máximo do arquivo em 2MB.
- Salvar com nome único (ex: UUID ou timestamp + nome sanitizado) para evitar sobrescrita de arquivos e vulnerabilidades de path traversal.

---

### Exercício 6.3: Helmet, CORS e Rate Limiting
**Objetivo:** Configurar na aplicação Express:
1. `cors` restrito apenas a domínios permitidos (ex: `http://localhost:3000`).
2. `helmet` para aplicar cabeçalhos de segurança HTTP (como CSP e HSTS).
3. `express-rate-limit` para limitar requisições em rotas de autenticação (máximo de 5 tentativas de login por minuto por IP).
