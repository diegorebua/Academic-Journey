# 🎯 Go — Intermediario

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_api_rest_stdlib](./01_api_rest_stdlib): Crie uma API REST CRUD para 'Produtos' usando apenas net/http com ServeMux.
- [02_api_rest_chi](./02_api_rest_chi): Refatore a API usando o roteador Chi com middlewares de log, CORS e autenticação.
- [03_banco_postgres](./03_banco_postgres): Conecte ao PostgreSQL usando pgx e implemente operações CRUD com prepared statements.
- [04_migrations_goose](./04_migrations_goose): Use goose ou migrate para gerenciar migrações de banco de dados.
- [05_goroutines_worker_pool](./05_goroutines_worker_pool): Implemente um Worker Pool com número fixo de goroutines processando tarefas de um channel.
- [06_select_statement](./06_select_statement): Use select para multiplexar channels: timeout, cancelamento e prioridade.
- [07_context_cancelamento](./07_context_cancelamento): Use context.Context para cancelar goroutines e propagar deadlines em requisições HTTP.
- [08_interface_avancada](./08_interface_avancada): Explore duck typing com interfaces: io.Reader, io.Writer, fmt.Stringer.
- [09_generics_go](./09_generics_go): Use generics (Go 1.18+) para criar funções e estruturas de dados genéricas: Map, Filter, Reduce.
- [10_testes_unitarios_go](./10_testes_unitarios_go): Escreva testes com testing, subtests (t.Run), testes de tabela e mocks com testify.
- [11_benchmarks_go](./11_benchmarks_go): Escreva benchmarks para comparar algoritmos (busca, ordenação) e otimize com os resultados.
- [12_middleware_cadeia](./12_middleware_cadeia): Crie uma cadeia de middlewares HTTP reutilizáveis: log, auth, rate limit, CORS.
- [13_jwt_auth](./13_jwt_auth): Implemente autenticação JWT: geração, validação e middleware de proteção de rotas.
- [14_grpc_go](./14_grpc_go): Crie um servidor e cliente gRPC com Protobuf para gerenciar usuários.
- [15_streaming_grpc](./15_streaming_grpc): Implemente gRPC com Server Streaming para transmitir resultados de busca progressivamente.
- [16_rabbitmq_go](./16_rabbitmq_go): Publique e consuma mensagens no RabbitMQ usando amqp091-go.
- [17_redis_go](./17_redis_go): Use Redis com go-redis para cache, pub/sub e listas de tarefas.
- [18_embed_arquivos](./18_embed_arquivos): Use go:embed para incluir arquivos estáticos (HTML, SQL, configs) no binário.
- [19_reflection_go](./19_reflection_go): Explore o pacote reflect para criar funções genéricas antes dos generics e validadores.
- [20_plugin_go](./20_plugin_go): Compile e carregue plugins Go dinâmicos em runtime usando o pacote plugin.
- [21_profiling_pprof](./21_profiling_pprof): Profile a aplicação com pprof: CPU, memória e goroutine leak detection.
- [22_cli_cobra](./22_cli_cobra): Crie uma CLI robusta com sub-comandos usando Cobra e Viper.
- [23_websocket_go](./23_websocket_go): Implemente um servidor WebSocket com gorilla/websocket para um chat em tempo real.
- [24_tls_https](./24_tls_https): Configure HTTPS com TLS usando certificados auto-assinados no servidor Go.
- [25_graceful_shutdown_go](./25_graceful_shutdown_go): Implemente graceful shutdown aguardando todas as requisições finalizarem.
- [26_rate_limiting_go](./26_rate_limiting_go): Implemente rate limiting com golang.org/x/time/rate (Token Bucket).
- [27_dependency_injection_go](./27_dependency_injection_go): Use wire ou fx para gerenciar injeção de dependências em uma aplicação maior.
- [28_mock_interfaces_go](./28_mock_interfaces_go): Use mockery para gerar mocks de interfaces e escreva testes de unidade isolados.
- [29_pipeline_funcional_go](./29_pipeline_funcional_go): Implemente pipeline de processamento de dados usando goroutines e channels encadeados.
- [30_xml_yaml_go](./30_xml_yaml_go): Serialize e desserialize dados em XML e YAML. Compare com JSON.
