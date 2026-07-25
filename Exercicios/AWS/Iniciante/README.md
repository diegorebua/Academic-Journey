# 🎯 AWS — Iniciante

**Total de exercícios neste nível:** 30

## 📝 Lista de Exercícios

- [01_s3_bucket_estatico](./01_s3_bucket_estatico): Crie um bucket S3, habilite hospedagem de site estático e suba um HTML simples.
- [02_iam_usuarios_grupos](./02_iam_usuarios_grupos): Crie usuários IAM, grupos e políticas. Entenda o princípio do menor privilégio.
- [03_ec2_instancia_basica](./03_ec2_instancia_basica): Suba uma instância EC2 t3.micro, conecte via SSH e instale o nginx.
- [04_security_groups](./04_security_groups): Configure Security Groups para permitir apenas tráfego HTTP e SSH de IPs específicos.
- [05_elastic_ip](./05_elastic_ip): Associe um Elastic IP à sua EC2 para ter um IP público fixo.
- [06_s3_versionamento](./06_s3_versionamento): Habilite versionamento no S3. Faça upload de versões do mesmo arquivo e restaure uma versão anterior.
- [07_cloudfront_cdn](./07_cloudfront_cdn): Configure o CloudFront em frente ao seu bucket S3 para distribuição global de conteúdo.
- [08_rds_free_tier](./08_rds_free_tier): Crie uma instância RDS PostgreSQL no free tier e conecte usando DBeaver ou psql.
- [09_vpc_basica](./09_vpc_basica): Crie uma VPC com subnets públicas e privadas, Internet Gateway e route tables.
- [10_elb_basico](./10_elb_basico): Configure um Application Load Balancer (ALB) na frente de duas instâncias EC2.
- [11_auto_scaling_group](./11_auto_scaling_group): Crie um Auto Scaling Group que escala EC2 baseado em uso de CPU.
- [12_cloudwatch_alarmes](./12_cloudwatch_alarmes): Configure alarmes no CloudWatch para notificar via SNS quando o CPU ultrapassar 80%.
- [13_sns_sqs_basico](./13_sns_sqs_basico): Publique uma mensagem no SNS e receba-a via SQS. Entenda fan-out.
- [14_lambda_hello](./14_lambda_hello): Crie uma função Lambda em Node.js que retorna 'Olá, Mundo!' e analise a execução nos logs.
- [15_api_gateway_lambda](./15_api_gateway_lambda): Exponha sua função Lambda via API Gateway REST e teste com curl.
- [16_dynamodb_basico](./16_dynamodb_basico): Crie uma tabela DynamoDB, insira, leia e delete itens usando o console e SDK.
- [17_cognito_basico](./17_cognito_basico): Configure o Cognito User Pool para autenticação e crie um fluxo de cadastro/login.
- [18_route53_dns](./18_route53_dns): Configure o Route 53 para apontar um domínio para seu CloudFront ou EC2.
- [19_certificate_manager](./19_certificate_manager): Emita um certificado SSL gratuito com o ACM e associe ao CloudFront e ALB.
- [20_systems_manager](./20_systems_manager): Use o SSM Session Manager para se conectar a EC2 sem abrir a porta 22.
- [21_s3_lifecycle](./21_s3_lifecycle): Configure regras de ciclo de vida no S3: mover para Glacier após 30 dias, deletar após 1 ano.
- [22_billing_budgets](./22_billing_budgets): Configure alertas de faturamento no Billing e Budgets para evitar surpresas na conta.
- [23_cloudtrail_basico](./23_cloudtrail_basico): Habilite o CloudTrail para auditar todas as chamadas de API feitas na sua conta.
- [24_parameter_store](./24_parameter_store): Armazene segredos (senha de banco, chave de API) no Parameter Store e acesse da Lambda.
- [25_ecr_docker](./25_ecr_docker): Crie um repositório no ECR, faça o build de uma imagem Docker e faça push.
- [26_ecs_fargate_simples](./26_ecs_fargate_simples): Rode um container Docker no ECS Fargate com uma task definition simples.
- [27_step_functions_basico](./27_step_functions_basico): Crie um workflow simples no Step Functions que encadeia duas funções Lambda.
- [28_glue_basico](./28_glue_basico): Use o AWS Glue Crawler para catalogar um dataset CSV no S3 e consultar com Athena.
- [29_kinesis_basico](./29_kinesis_basico): Crie um Kinesis Data Stream e produza/consuma mensagens com o SDK.
- [30_well_architected_review](./30_well_architected_review): Avalie sua arquitetura usando o AWS Well-Architected Framework (os 6 pilares).
