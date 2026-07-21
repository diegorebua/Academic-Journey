# Nível 9: Especialista (Arquitetura em Camadas, Testes Unitários e E2E)

Neste nível você aplicará princípios de Clean Architecture/Design de Código e garantirá a qualidade do sistema com cobertura de testes (Jest / Vitest / Supertest).

---

### Exercício 9.1: Refatoração para Arquitetura em Camadas e Inversão de Dependência
**Objetivo:** Refatorar o módulo de Usuários para separar responsabilidades rigorosamente:
- `UserController`: Trata requisições e respostas HTTP.
- `UserService`: Contém todas as regras de negócio puras (sem dependência direta de Express).
- `UserRepository`: Interface/Contrato abstrato de banco de dados (permitindo trocar facilmente a implementação de banco).

---

### Exercício 9.2: Testes Unitários da Camada de Service
**Objetivo:** Escrever testes unitários com Jest ou Vitest para o `UserService`:
- Testar criação de usuário com sucesso (usando *Mock* do Repository).
- Testar tentativa de cadastro com e-mail duplicado (garantindo que lança a exceção correta sem tocar no banco de dados real).

---

### Exercício 9.3: Testes de Integração E2E (End-to-End)
**Objetivo:** Criar uma suíte de testes de integração com `supertest` que teste o fluxo completo na API HTTP real:
1. Enviar requisição POST para registrar usuário.
2. Realizar login com as credenciais criadas e obter o token JWT.
3. Usar o token JWT para acessar a rota protegida e verificar os dados retornados.
