# 🎯 SQL — Iniciante

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_select_basico](./01_select_basico): Use SELECT para buscar todas as colunas e colunas específicas de uma tabela.
- [02_where_filtros](./02_where_filtros): Filtre registros com WHERE usando =, !=, >, <, BETWEEN, IN e LIKE.
- [03_order_by_limit](./03_order_by_limit): Ordene resultados com ORDER BY (ASC e DESC) e limite com LIMIT/OFFSET.
- [04_operadores_logicos](./04_operadores_logicos): Combine condições com AND, OR e NOT no WHERE.
- [05_funcoes_agregacao](./05_funcoes_agregacao): Use COUNT, SUM, AVG, MIN e MAX para sumarizar dados.
- [06_group_by_having](./06_group_by_having): Agrupe resultados com GROUP BY e filtre grupos com HAVING.
- [07_alias_colunas_tabelas](./07_alias_colunas_tabelas): Use AS para criar aliases de colunas e tabelas para legibilidade.
- [08_insert_dados](./08_insert_dados): Insira dados com INSERT INTO: linha única e múltiplas linhas.
- [09_update_dados](./09_update_dados): Atualize registros com UPDATE. CUIDADO: sempre use WHERE para não atualizar tudo.
- [10_delete_dados](./10_delete_dados): Delete registros com DELETE. Use transactions para segurança.
- [11_criar_tabela](./11_criar_tabela): Crie tabelas com CREATE TABLE definindo tipos e constraints (NOT NULL, UNIQUE, DEFAULT).
- [12_primary_foreign_key](./12_primary_foreign_key): Defina PRIMARY KEY e FOREIGN KEY. Entenda integridade referencial.
- [13_inner_join](./13_inner_join): Una duas tabelas com INNER JOIN. Filtre apenas os registros que têm correspondência em ambas.
- [14_left_right_join](./14_left_right_join): Use LEFT JOIN e RIGHT JOIN. Entenda a diferença com INNER JOIN.
- [15_full_outer_join](./15_full_outer_join): Use FULL OUTER JOIN para incluir todos os registros de ambas as tabelas.
- [16_self_join](./16_self_join): Use SELF JOIN para comparar linhas dentro da mesma tabela.
- [17_subquery_simples](./17_subquery_simples): Use subqueries no WHERE para filtrar com base em resultados de outra query.
- [18_distinct_uniqueness](./18_distinct_uniqueness): Use DISTINCT para eliminar duplicatas em resultados.
- [19_null_handling](./19_null_handling): Trate valores NULL com IS NULL, IS NOT NULL e COALESCE.
- [20_tipos_dados_sql](./20_tipos_dados_sql): Explore os tipos de dados: VARCHAR, TEXT, INTEGER, NUMERIC, DATE, TIMESTAMP, BOOLEAN.
- [21_constraints_check](./21_constraints_check): Adicione constraints CHECK para validar dados na criação (ex: idade > 0).
- [22_alter_table](./22_alter_table): Modifique tabelas com ALTER TABLE: adicionar/remover colunas, renomear.
- [23_truncate_drop](./23_truncate_drop): Entenda a diferença entre TRUNCATE, DELETE sem WHERE e DROP TABLE.
- [24_case_when](./24_case_when): Use CASE WHEN para criar lógica condicional dentro de uma query.
- [25_concatenar_strings](./25_concatenar_strings): Use CONCAT, ||, UPPER, LOWER, TRIM, SUBSTRING e LENGTH em campos de texto.
- [26_funcoes_data_hora](./26_funcoes_data_hora): Use NOW(), CURRENT_DATE, DATE_PART, AGE e EXTRACT para manipular datas.
- [27_like_ilike](./27_like_ilike): Use LIKE e ILIKE para buscas por padrão. Entenda a performance.
- [28_union_intersect_except](./28_union_intersect_except): Use UNION, INTERSECT e EXCEPT para combinar resultados de múltiplas queries.
- [29_transacoes_basico](./29_transacoes_basico): Use BEGIN, COMMIT e ROLLBACK para agrupar operações em uma transação.
- [30_modelo_dados_livraria](./30_modelo_dados_livraria): Crie o modelo de dados completo de uma livraria: Livros, Autores, Clientes, Pedidos.
