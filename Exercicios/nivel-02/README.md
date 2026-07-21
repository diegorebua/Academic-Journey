# Nível 2: Iniciante+ (Assincronismo, Promises e Async/Await)

Neste nível você lidará com operações assíncronas, consumo de APIs externas e tratamento rigoroso de exceções com `try/catch`.

---

### Exercício 2.1: Simulação de Busca com Delay
**Objetivo:** Crie uma função `buscarUsuarioPorId(id)` que retorne uma `Promise`. Se o `id` for maior que 0, resolva a promise após 1 segundo com `{ id, nome: "Usuário " + id }`. Se o `id <= 0`, rejeite a promise com a mensagem `"ID inválido"`.

---

### Exercício 2.2: Consumo de API Externa
**Objetivo:** Escreva uma função assíncrona `buscarCEP(cep)` usando `fetch` ou `axios` para consultar a API `https://viacep.com.br/ws/{cep}/json/`. Retorne apenas as propriedades `{ logradouro, bairro, localidade, uf }`.

---

### Exercício 2.3: Execução Paralela com Promise.all
**Objetivo:** Crie a função `carregarDashboard(usuarioId)` que faça 3 chamadas assíncronas simultâneas (Perfil, Notificações e Compras) em paralelo usando `Promise.all` e retorne um objeto unificado com os 3 resultados.
