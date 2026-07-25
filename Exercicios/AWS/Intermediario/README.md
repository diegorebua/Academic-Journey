# 🎯 AWS — Intermediario

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_vpc_avancada](./01_vpc_avancada): Projete uma VPC multi-AZ com subnets públicas/privadas, NAT Gateway e VPC Endpoints.
- [02_ecs_fargate_api](./02_ecs_fargate_api): Faça o deploy de uma API Node.js containerizada no ECS Fargate com ALB e auto-scaling.
- [03_rds_alta_disponibilidade](./03_rds_alta_disponibilidade): Configure RDS Multi-AZ com read replicas e failover automático.
- [04_elasticache_redis](./04_elasticache_redis): Configure ElastiCache Redis para cache de sessões e resultados de API.
- [05_sqs_lambda_processamento](./05_sqs_lambda_processamento): Crie um pipeline assíncrono: API → SQS → Lambda processando em lote (batch).
- [06_s3_event_trigger](./06_s3_event_trigger): Dispare uma Lambda automaticamente quando um arquivo for enviado ao S3.
- [07_codepipeline_cicd](./07_codepipeline_cicd): Configure um pipeline CI/CD com CodePipeline, CodeBuild e CodeDeploy para um app Node.js.
- [08_cloudformation_basico](./08_cloudformation_basico): Provisione uma stack (EC2 + RDS + Security Groups) com um template CloudFormation.
- [09_terraform_basico](./09_terraform_basico): Provisione a mesma infraestrutura do exercício anterior usando Terraform.
- [10_secrets_manager](./10_secrets_manager): Armazene e recupere segredos de banco de dados com Secrets Manager com rotação automática.
- [11_waf_shield](./11_waf_shield): Configure o WAF na frente do CloudFront para bloquear SQLi e XSS.
- [12_guardduty](./12_guardduty): Habilite o GuardDuty e simule um ataque para ver as findings geradas.
- [13_config_rules](./13_config_rules): Configure regras do AWS Config para auditoria de conformidade (ex: S3 sem criptografia).
- [14_xray_tracing](./14_xray_tracing): Adicione rastreamento com X-Ray a uma função Lambda e uma API Gateway.
- [15_eventbridge_rules](./15_eventbridge_rules): Configure regras no EventBridge para reagir a eventos de outros serviços AWS.
- [16_sfn_workflow_avancado](./16_sfn_workflow_avancado): Crie um workflow Step Functions com states de erro, retry e parallel.
- [17_opensearch_basico](./17_opensearch_basico): Configure o OpenSearch Service e indexe documentos para busca full-text.
- [18_msk_kafka](./18_msk_kafka): Configure o MSK (Managed Streaming for Kafka) e crie producers/consumers.
- [19_appsync_graphql](./19_appsync_graphql): Crie uma API GraphQL com AppSync conectada ao DynamoDB.
- [20_amplify_frontend](./20_amplify_frontend): Faça o deploy de um app React no AWS Amplify com CI/CD integrado ao GitHub.
- [21_s3_replication](./21_s3_replication): Configure replicação entre buckets S3 em regiões diferentes para disaster recovery.
- [22_global_accelerator](./22_global_accelerator): Configure o AWS Global Accelerator para reduzir latência em aplicações globais.
- [23_lambda_layers](./23_lambda_layers): Crie Lambda Layers para compartilhar dependências entre múltiplas funções.
- [24_lambda_powertools](./24_lambda_powertools): Use AWS Lambda Powertools para logging estruturado, tracing e métricas.
- [25_data_pipeline_glue](./25_data_pipeline_glue): Crie um pipeline ETL completo com Glue: S3 → transformação → Redshift.
- [26_athena_s3](./26_athena_s3): Consulte dados em S3 com Athena usando SQL e otimize o custo com Parquet.
- [27_iam_roles_avancado](./27_iam_roles_avancado): Configure Cross-Account Roles, Permission Boundaries e Service Control Policies.
- [28_network_firewall](./28_network_firewall): Configure o AWS Network Firewall para inspecionar tráfego na VPC.
- [29_disaster_recovery](./29_disaster_recovery): Implemente uma estratégia de Pilot Light para disaster recovery multi-região.
- [30_cost_optimization](./30_cost_optimization): Analise os custos usando Cost Explorer, Trusted Advisor e implemente 5 otimizações.
