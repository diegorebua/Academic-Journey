# 🎯 NodeJS — Avancado

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_clean_architecture](./01_clean_architecture): Refatore a API para Clean Architecture com camadas separadas: Domain, Application, Infrastructure.
- [02_cqrs_event_sourcing](./02_cqrs_event_sourcing): Implemente CQRS com Event Sourcing: estados derivados de eventos imutáveis, com replay.
- [03_microservicos_comunicacao](./03_microservicos_comunicacao): Crie dois microserviços que se comunicam via RabbitMQ (Pub/Sub e Work Queues).
- [04_kafka_streaming](./04_kafka_streaming): Configure Apache Kafka e crie um producer/consumer para processar eventos em alta escala.
- [05_ddd_dominio](./05_ddd_dominio): Modele um domínio de e-commerce usando DDD: Aggregates, Entities, Value Objects, Repositories.
- [06_performance_profiling](./06_performance_profiling): Profile e otimize uma API lenta usando clinic.js, flame graphs e v8-profiler.
- [07_memory_leaks](./07_memory_leaks): Encontre e corrija memory leaks em uma aplicação Node.js usando heapdump e Chrome DevTools.
- [08_worker_threads](./08_worker_threads): Use worker_threads para processamento paralelo de CPU-intensive tasks.
- [09_custom_runtime](./09_custom_runtime): Crie um runtime customizado usando vm.Script ou vm.Module para execução segura de código.
- [10_plugin_system](./10_plugin_system): Implemente um sistema de plugins dinâmicos que carrega módulos em runtime.
- [11_distributed_tracing](./11_distributed_tracing): Adicione distributed tracing com OpenTelemetry e Jaeger para rastrear requisições entre serviços.
- [12_feature_flags](./12_feature_flags): Implemente um sistema de feature flags com rollout gradual e targeting de usuários.
- [13_api_mesh](./13_api_mesh): Configure uma camada de API Mesh com Apollo Federation juntando múltiplos subgraphs GraphQL.
- [14_saga_pattern](./14_saga_pattern): Implemente o padrão Saga (coreografia e orquestração) para transações distribuídas.
- [15_outbox_pattern](./15_outbox_pattern): Implemente o padrão Outbox para garantir entrega de eventos sem perda em falhas parciais.
- [16_schema_registry](./16_schema_registry): Configure um Schema Registry para validar mensagens Kafka com Avro schemas.
- [17_blue_green_deployment](./17_blue_green_deployment): Implemente Blue-Green Deployment com zero downtime na troca de versões.
- [18_chaos_engineering](./18_chaos_engineering): Crie testes de Chaos Engineering simulando falhas de rede, latência e crashes.
- [19_observabilidade_stack](./19_observabilidade_stack): Configure uma stack completa de observabilidade: Prometheus + Grafana + Loki.
- [20_node_custom_gc](./20_node_custom_gc): Experimente e configure o Garbage Collector do V8 para otimizar o consumo de memória.
- [21_native_addon](./21_native_addon): Crie um Native Addon em C++ usando node-addon-api para expor uma funcionalidade de sistema.
- [22_snapshot_testing](./22_snapshot_testing): Implemente snapshot testing da API e do banco de dados para detectar regressões.
- [23_contract_testing](./23_contract_testing): Implemente Consumer-Driven Contract Testing com Pact entre serviços.
- [24_api_rate_throttle_avancado](./24_api_rate_throttle_avancado): Implemente rate limiting distribuído usando Redis com o algoritmo Token Bucket.
- [25_multi_region_deploy](./25_multi_region_deploy): Projete e documente um deploy multi-região com failover automático e latência mínima.
- [26_zero_trust_security](./26_zero_trust_security): Implemente uma arquitetura Zero Trust com autenticação mútua (mTLS) entre serviços.
- [27_serverless_local](./27_serverless_local): Emule o ambiente de Lambda com serverless-offline e escreva funções serverless em Node.js.
- [28_wasm_node](./28_wasm_node): Integre um módulo WebAssembly de alta performance em uma API Node.js.
- [29_event_loop_internals](./29_event_loop_internals): Crie exemplos que demonstram cada fase do Event Loop: timers, I/O, idle, check, close.
- [30_node_stream_backpressure](./30_node_stream_backpressure): Implemente um pipeline de Streams com controle de backpressure para não estourar memória.
