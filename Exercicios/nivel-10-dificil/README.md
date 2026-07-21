# Nível 10: Mestre (Microserviços, Filas Assíncronas, Webhooks & Resilience - Difícil)

Neste nível você lidará com sistemas distribuídos de alta complexidade, assincronismo de longo prazo, filas de mensageria e segurança de webhooks.

---

### Exercício 10.1: Processamento em Fila Assíncrona com Redis e BullMQ
**Objetivo:** Implementar um serviço de envio de e-mails/relatórios pesados utilizando **BullMQ** e **Redis**:
- O endpoint `POST /relatorios` deve disparar a geração do relatório e retornar `202 Accepted` imediatamente com o ID do job.
- O worker da fila processa o relatório em segundo plano.
- Implementar política de retry (*Exponential Backoff*) em caso de falha temporária no worker.

---

### Exercício 10.2: Sistema de Webhooks Seguro com Assinatura HMAC
**Objetivo:** Criar um sistema de envio e recebimento de Webhooks:
- Ao ocorrer um evento (ex: `pedido.pago`), o sistema dispara um HTTP POST para URLs cadastradas por clientes.
- Incluir no cabeçalho `X-Signature` o hash HMAC SHA-256 do payload gerado com um *secret* compartilhado.
- Escrever o código do cliente receptor que valida a assinatura `X-Signature` antes de processar o evento para prevenir falsificação de requisições.

---

### Exercício 10.3: Rate Limiter Distribuído & Cache L1/L2
**Objetivo:** Projetar e implementar um middleware de Rate Limiting distribuído utilizando Redis e algoritmo *Token Bucket* ou *Sliding Window Log*, garantindo que múltiplos containers da API respeitem o mesmo limite global de requisições sem inconsistências ou condições de corrida (*race conditions*).
