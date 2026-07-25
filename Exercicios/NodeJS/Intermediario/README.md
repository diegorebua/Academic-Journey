# 🎯 NodeJS — Intermediario

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_api_rest_express](./01_api_rest_express): Crie uma API REST CRUD completa para 'Produtos' usando Express com dados em memória.
- [02_middlewares_customizados](./02_middlewares_customizados): Implemente middlewares de autenticação JWT, log de requisições e tratamento de erros global.
- [03_banco_de_dados_sqlite](./03_banco_de_dados_sqlite): Conecte a API ao SQLite usando better-sqlite3. Implemente migrações e seeds.
- [04_upload_arquivos](./04_upload_arquivos): Implemente upload de arquivos com Multer: valide tipo, tamanho e salve com nome único.
- [05_rate_limiting](./05_rate_limiting): Adicione rate limiting à API com express-rate-limit e estratégias por IP e por usuário.
- [06_cache_redis](./06_cache_redis): Implemente cache de respostas de API usando Redis com invalidação por tempo e por evento.
- [07_filas_bullmq](./07_filas_bullmq): Use BullMQ para processar tarefas em background: envio de e-mail, geração de relatório.
- [08_websocket_socket_io](./08_websocket_socket_io): Crie um chat em tempo real com salas usando Socket.io, com histórico de mensagens.
- [09_autenticacao_completa](./09_autenticacao_completa): Implemente autenticação completa: registro, login, refresh token, logout e rota protegida.
- [10_testes_unitarios_jest](./10_testes_unitarios_jest): Escreva testes unitários com Jest para as funções de negócio da API (mocking de dependências).
- [11_testes_integracao_supertest](./11_testes_integracao_supertest): Escreva testes de integração com Supertest que testam os endpoints da API com banco real.
- [12_graphql_apollo](./12_graphql_apollo): Converta a API REST para GraphQL usando Apollo Server com queries, mutations e subscriptions.
- [13_grpc_server](./13_grpc_server): Crie um microserviço gRPC para gerenciar usuários com o protocolo Protobuf.
- [14_swagger_documentacao](./14_swagger_documentacao): Documente a API usando Swagger/OpenAPI com validação de schema em runtime.
- [15_cron_jobs](./15_cron_jobs): Agende tarefas recorrentes com node-cron: limpeza de sessões expiradas, envio de e-mails.
- [16_clustering](./16_clustering): Use o módulo cluster do Node.js para aproveitar múltiplos núcleos de CPU na API.
- [17_graceful_shutdown](./17_graceful_shutdown): Implemente graceful shutdown na API: finalize conexões abertas antes de encerrar o processo.
- [18_streams_processamento](./18_streams_processamento): Crie um pipeline de Streams para processar e transformar um arquivo CSV de 1GB linha por linha.
- [19_proxy_reverso](./19_proxy_reverso): Crie um proxy reverso simples que roteia requisições para diferentes microserviços.
- [20_api_gateway](./20_api_gateway): Crie um API Gateway que autentique e roteia requisições para serviços downstream.
- [21_passport_oauth](./21_passport_oauth): Implemente autenticação com OAuth 2.0 (Google/GitHub) usando Passport.js.
- [22_email_nodemailer](./22_email_nodemailer): Envie e-mails com templates HTML usando Nodemailer e um serviço SMTP.
- [23_pdf_generator](./23_pdf_generator): Gere PDFs de relatórios dinamicamente usando PDFKit ou Puppeteer.
- [24_image_processing](./24_image_processing): Processe imagens (resize, crop, watermark) usando Sharp de forma assíncrona.
- [25_crawler_cheerio](./25_crawler_cheerio): Crie um web crawler com Axios e Cheerio que extrai dados de uma página HTML.
- [26_real_time_dashboard](./26_real_time_dashboard): Crie um dashboard em tempo real com Server-Sent Events (SSE) exibindo métricas do sistema.
- [27_multi_tenancy](./27_multi_tenancy): Implemente multi-tenancy na API com isolamento de dados por subdomínio.
- [28_event_driven_arch](./28_event_driven_arch): Refatore a API para uma arquitetura orientada a eventos usando o EventEmitter interno.
- [29_api_versioning](./29_api_versioning): Implemente versionamento de API (/v1, /v2) com compatibilidade retroativa.
- [30_health_checks](./30_health_checks): Implemente health checks detalhados (/health, /ready, /live) para uso com orquestradores.
