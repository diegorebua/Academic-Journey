# Nível 7: Avançado (Frontend Integration - React / Vue & Estado Global)

Neste nível você integrará a API backend com uma aplicação Frontend (React ou Vue), lidando com reatividade, formulários e gerenciamento de estado.

---

### Exercício 7.1: Formulário Reativo com Validação
**Objetivo:** Criar um componente de Formulário de Cadastro (React/Vue) com validação em tempo real dos campos:
- E-mail com formato válido.
- Senha com no mínimo 8 caracteres, contendo pelo menos 1 letra maiúscula e 1 número.
- Exibir mensagens de erro amigáveis abaixo dos inputs.

---

### Exercício 7.2: Consumo de API com Tratamento de Estados
**Objetivo:** Criar uma lista paginada de produtos consumindo a API backend via Axios.
- Gerenciar explicitamente os estados: `loading` (spinner/skeleton), `error` (mensagem de erro com botão de re-tentativa) e `success` (renderização dos cards de produto).

---

### Exercício 7.3: Contexto de Autenticação (Auth Provider)
**Objetivo:** Criar um Context (React Context API) ou Store (Pinia/Vuex) para gerenciar o estado global de autenticação (`user`, `isAuthenticated`, `login`, `logout`). Salvar e recuperar o Access Token com segurança no `localStorage` ou `httpOnly cookie`.
