# Nível 5: Intermediário+ (Autenticação JWT, Hash de Senhas e AuthGuard)

Neste nível você implementará fluxos reais de segurança, hashing seguro de senhas com `bcrypt` e proteção de rotas com JWT (JSON Web Token).

---

### Exercício 5.1: Registro e Hash de Senha com Bcrypt
**Objetivo:** Criar a rota `POST /auth/register` que receba `email` e `senha`. A senha deve ser criptografada usando `bcrypt.hash` (com salt 10) antes de ser salva no banco de dados. Nunca salve senhas em texto puro!

---

### Exercício 5.2: Geração e Validação de Access Token (JWT)
**Objetivo:** Criar a rota `POST /auth/login` que valide o e-mail e a senha com `bcrypt.compare`. Se válidos, gere e retorne um JWT contendo os claims `{ sub: usuario.id, email: usuario.email }` com expiração de 15 minutos.

---

### Exercício 5.3: Middleware AuthGuard (Proteção de Rotas)
**Objetivo:** Criar o middleware `authGuard` que extraia o token do cabeçalho `Authorization: Bearer <token>`, valide a assinatura do JWT e anexe os dados do usuário em `req.user`. Caso o token seja ausente ou inválido, retorne `401 Unauthorized`.
