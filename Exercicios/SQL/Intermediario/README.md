# 🎯 SQL — Intermediario

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_cte_common_table_expressions](./01_cte_common_table_expressions): Use CTEs (WITH) para organizar queries complexas em partes legíveis.
- [02_window_functions_row_number](./02_window_functions_row_number): Use ROW_NUMBER(), RANK() e DENSE_RANK() para ranking de registros.
- [03_window_lag_lead](./03_window_lag_lead): Use LAG() e LEAD() para comparar um registro com o anterior e o próximo.
- [04_window_running_total](./04_window_running_total): Calcule totais acumulados com SUM() OVER (ORDER BY ...).
- [05_recursive_cte](./05_recursive_cte): Crie CTEs recursivas para navegar em hierarquias (organograma, categorias).
- [06_indices_criacao](./06_indices_criacao): Crie índices simples e compostos. Entenda como eles aceleram buscas.
- [07_explain_analyze](./07_explain_analyze): Use EXPLAIN ANALYZE para analisar o plano de execução e identificar queries lentas.
- [08_subquery_correlacionada](./08_subquery_correlacionada): Escreva subqueries correlacionadas que referenciam a query externa.
- [09_exists_not_exists](./09_exists_not_exists): Use EXISTS e NOT EXISTS como alternativa performática a IN com grandes datasets.
- [10_lateral_join](./10_lateral_join): Use LATERAL JOIN para referenciar colunas de tabelas anteriores no FROM.
- [11_json_postgresql](./11_json_postgresql): Armazene e consulte dados JSON/JSONB no PostgreSQL com operadores específicos.
- [12_array_postgresql](./12_array_postgresql): Use colunas do tipo ARRAY no PostgreSQL com operadores de array.
- [13_funcoes_sql](./13_funcoes_sql): Crie funções SQL reutilizáveis (CREATE FUNCTION) para lógica de negócio.
- [14_stored_procedures](./14_stored_procedures): Crie stored procedures com lógica condicional e loops em PL/pgSQL.
- [15_triggers](./15_triggers): Crie triggers para auditoria automática: registre quem e quando modificou cada linha.
- [16_views](./16_views): Crie views para simplificar queries complexas e controlar acesso a dados.
- [17_materialized_views](./17_materialized_views): Crie Materialized Views para consultas pesadas e configure refresh periódico.
- [18_particoes_tabela](./18_particoes_tabela): Implemente particionamento de tabelas por range (data) e por lista (região).
- [19_upsert_on_conflict](./19_upsert_on_conflict): Use INSERT ... ON CONFLICT (DO UPDATE / DO NOTHING) para upsert idiomático.
- [20_sequences_serials](./20_sequences_serials): Use SEQUENCES e GENERATED ALWAYS AS IDENTITY para chaves primárias.
- [21_schemas_namespaces](./21_schemas_namespaces): Organize tabelas em schemas separados e controle acesso por schema.
- [22_full_text_search](./22_full_text_search): Configure Full Text Search: tsvector, tsquery, GIN index e relevância.
- [23_regex_sql](./23_regex_sql): Use expressões regulares no SQL com SIMILAR TO e ~ (regexp).
- [24_pivot_crosstab](./24_pivot_crosstab): Crie queries pivot (tabelas cruzadas) com o tablefunc e crosstab.
- [25_temporal_data](./25_temporal_data): Gerencie dados históricos com bitemporalidade (valid_time e transaction_time).
- [26_soft_delete](./26_soft_delete): Implemente soft delete com uma coluna deleted_at e filtre com views.
- [27_row_level_security](./27_row_level_security): Configure Row Level Security no PostgreSQL para multi-tenancy no nível de linha.
- [28_performance_tuning_sql](./28_performance_tuning_sql): Otimize 5 queries lentas: reescreva, adicione índices e analise o plano.
- [29_modelo_ecommerce](./29_modelo_ecommerce): Projete o schema de um e-commerce: Produtos, Estoque, Pedidos, Pagamentos, Entregas.
- [30_relatorio_vendas](./30_relatorio_vendas): Escreva um relatório complexo de vendas usando CTEs, window functions e aggregations.
