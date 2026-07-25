# 🎯 SQL — Avancado

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_query_optimizer](./01_query_optimizer): Entenda profundamente o Query Optimizer do PostgreSQL: estatísticas, planos, hints.
- [02_index_types](./02_index_types): Explore os tipos de índice: B-Tree, Hash, GIN, GiST, SP-GiST, BRIN. Quando usar cada um.
- [03_index_only_scan](./03_index_only_scan): Configure índices covering para atingir Index-Only Scans e eliminar acesso à tabela.
- [04_parallel_query](./04_parallel_query): Habilite e configure Parallel Query no PostgreSQL para queries pesadas.
- [05_connection_pooling](./05_connection_pooling): Configure PgBouncer para pooling de conexões e compare os modos transaction/session.
- [06_wal_replication](./06_wal_replication): Configure streaming replication com WAL para um standby de leitura.
- [07_logical_replication](./07_logical_replication): Configure Logical Replication para replicar tabelas específicas entre bancos.
- [08_point_in_time_recovery](./08_point_in_time_recovery): Configure PITR usando WAL archives para restaurar o banco a um momento específico.
- [09_vacuum_autovacuum](./09_vacuum_autovacuum): Entenda VACUUM, AUTOVACUUM, table bloat e como monitorar e tunar o autovacuum.
- [10_toast_storage](./10_toast_storage): Entenda o mecanismo TOAST para armazenamento de dados grandes e seu impacto.
- [11_mvcc_internals](./11_mvcc_internals): Estude o MVCC (Multi-Version Concurrency Control) do PostgreSQL: xmin, xmax, cid.
- [12_lock_monitoring](./12_lock_monitoring): Monitore e resolva deadlocks e lock contention com pg_locks e pg_stat_activity.
- [13_advisory_locks](./13_advisory_locks): Use Advisory Locks para coordenação de processos sem bloqueio de linhas.
- [14_fdw_foreign_tables](./14_fdw_foreign_tables): Configure Foreign Data Wrappers para consultar dados externos (MySQL, MongoDB, S3).
- [15_pl_pgsql_avancado](./15_pl_pgsql_avancado): Escreva stored procedures complexas com cursores, exception handling e dynamic SQL.
- [16_pl_python](./16_pl_python): Use PL/Python para escrever funções no banco que executam código Python.
- [17_custom_aggregate](./17_custom_aggregate): Crie uma função de agregação customizada em C ou PL/pgSQL.
- [18_custom_operator](./18_custom_operator): Defina um operador customizado para tipos de dados do seu domínio.
- [19_domain_types](./19_domain_types): Crie Domain Types para representar tipos de negócio com validação (email, CPF).
- [20_range_types](./20_range_types): Use Range Types (int4range, tsrange) para modelar intervalos e verificar sobreposições.
- [21_sharding_citus](./21_sharding_citus): Configure sharding horizontal com a extensão Citus para escala de escrita.
- [22_timescaledb](./22_timescaledb): Use TimescaleDB para dados de série temporal com compressão e continuous aggregates.
- [23_postgis_geoespacial](./23_postgis_geoespacial): Configure PostGIS e escreva queries geoespaciais para encontrar pontos dentro de polígonos.
- [24_pg_stat_statements](./24_pg_stat_statements): Habilite pg_stat_statements para identificar as queries mais custosas em produção.
- [25_hypothetical_indexes](./25_hypothetical_indexes): Use a extensão HypoPG para simular índices sem criá-los de fato.
- [26_data_versioning_temporal](./26_data_versioning_temporal): Implemente versionamento completo de dados usando a extensão temporal_tables ou Hibernate Envers.
- [27_schema_migration_zero_downtime](./27_schema_migration_zero_downtime): Execute migrações de schema sem downtime: expand-contract, backfill e rename.
- [28_benchmark_pgbench](./28_benchmark_pgbench): Benchmark o banco de dados com pgbench, analise TPS e identifique gargalos.
- [29_distributed_transactions](./29_distributed_transactions): Implemente distributed transactions entre dois bancos PostgreSQL usando 2PC (Two-Phase Commit).
- [30_database_design_principles](./30_database_design_principles): Documente as melhores práticas de design de banco de dados: normalização, desnormalização estratégica e modelagem de domínio.
