# 🎯 Go — Avancado

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_clean_arch_go](./01_clean_arch_go): Implemente Clean Architecture em Go: Domain, Use Cases, Interface Adapters, Frameworks.
- [02_ddd_go](./02_ddd_go): Modele um domínio bancário com DDD: Aggregates, Entities, Value Objects e Domain Events.
- [03_event_sourcing_go](./03_event_sourcing_go): Implemente Event Sourcing com EventStore e replay de eventos para reconstruir estado.
- [04_saga_go](./04_saga_go): Implemente o padrão Saga para uma transação distribuída de compra com compensação.
- [05_kafka_go](./05_kafka_go): Produza e consuma mensagens no Kafka usando confluent-kafka-go com grupos de consumo.
- [06_raft_consensus](./06_raft_consensus): Implemente o algoritmo de consenso Raft simplificado em Go usando goroutines.
- [07_scheduler_distribuido](./07_scheduler_distribuido): Crie um scheduler distribuído tolerante a falhas usando etcd para eleição de líder.
- [08_custom_garbage_collector](./08_custom_garbage_collector): Implemente um alocador de memória simples com garbage collection por referência.
- [09_assembly_go](./09_assembly_go): Escreva funções em assembly x86-64 chamadas a partir do Go para operações SIMD.
- [10_network_raw_socket](./10_network_raw_socket): Use raw sockets para criar um scanner de portas TCP (similar ao nmap) do zero.
- [11_compiler_go](./11_compiler_go): Crie um compilador de uma linguagem simples usando o toolchain Go (go/parser, go/ast).
- [12_cgo_integracao](./12_cgo_integracao): Integre código C em Go com cgo: chame funções C e passe structs entre as duas linguagens.
- [13_wasm_go](./13_wasm_go): Compile um programa Go para WebAssembly e integre-o em uma página HTML.
- [14_distributed_lock](./14_distributed_lock): Implemente um Distributed Lock usando Redis (Redlock algorithm).
- [15_service_mesh_sidecar](./15_service_mesh_sidecar): Implemente um sidecar proxy em Go para interceptar e logar tráfego de rede.
- [16_consensus_paxos](./16_consensus_paxos): Implemente o algoritmo Paxos (single-decree) em Go para entender consenso distribuído.
- [17_lsm_tree](./17_lsm_tree): Implemente um LSM-Tree (Log-Structured Merge-Tree) simplificado: MemTable e SSTable.
- [18_b_tree_go](./18_b_tree_go): Implemente uma B-Tree em Go com inserção, busca e deleção.
- [19_query_engine](./19_query_engine): Crie um query engine SQL simplificado que analisa e executa SELECTs básicos.
- [20_bloom_filter](./20_bloom_filter): Implemente um Bloom Filter probabilístico e use-o para verificar membership.
- [21_hyperloglog_go](./21_hyperloglog_go): Implemente o algoritmo HyperLogLog para estimativa de cardinalidade.
- [22_circuit_breaker_go](./22_circuit_breaker_go): Implemente Circuit Breaker com estados e transições em Go para chamadas de serviços.
- [23_zero_copy_go](./23_zero_copy_go): Use técnicas de zero-copy (sendfile, splice) para transferência eficiente de arquivos.
- [24_lock_free_structures](./24_lock_free_structures): Implemente estruturas lock-free (fila MPMC) usando sync/atomic.
- [25_custom_tcp_protocol](./25_custom_tcp_protocol): Defina e implemente um protocolo TCP binário customizado (framing, encoding, handling).
- [26_distributed_cache](./26_distributed_cache): Construa um cache distribuído consistente com hashing consistente e replicação.
- [27_tracing_opentelemetry_go](./27_tracing_opentelemetry_go): Configure distributed tracing com OpenTelemetry e exporte para Jaeger.
- [28_mutation_testing_go](./28_mutation_testing_go): Configure mutation testing com go-mutesting para verificar a qualidade dos testes.
- [29_generics_advanced](./29_generics_advanced): Explore os limites dos generics em Go: constraints complexas, type sets e instâncias.
- [30_interpreter_go](./30_interpreter_go): Implemente um interpretador completo (lexer, parser, avaliador) para uma linguagem de script.
