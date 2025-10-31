# AWS-LocalStack
Amazon S3

O Amazon S3 permite armazenar e acessar dados de forma simples e segura, sendo ideal para backup e armazenamento.

Vantagens:

-Alta durabilidade e disponibilidade
-Escalabilidade para grandes volumes de dados
-Segurança avançada para proteger suas informações



AWS Lambda

O AWS Lambda é um serviço de computação serverless, permitindo executar código em resposta a eventos, sem a necessidade de gerenciar servidores.

Características:

-Escalável e seguro
-Suporta múltiplas linguagens
-Custo eficiente, pois não há servidor dedicado
-Execução ideal de até 15 minutos, podendo criar várias funções Lambda

Vantagens:

-Execução sob demanda
-Escalabilidade automática
-Custo eficiente
-Integração com outros serviços AWS

LocalStack

O LocalStack é um projeto open-source que fornece uma alternativa local para desenvolvimento, teste e integração de serviços em nuvem, sem acessar a AWS real.

Benefícios:

-Economiza tempo e custos no desenvolvimento
-Ideal para testes automatizados
-Facilita o uso em ambientes de integração contínua (CI/CD)

Tarefas para Configuração:
	1) Criar o bucket S3: Configure um bucket chamado notas-fiscais-upload
	2) Criar a tabela no DynamoDB: Nome NotasFiscais, com chave primária id.
	3) Criar uma Lambda Function: Configure as permissões para acesso ao S3 e DynamoDB.
	4) Criar o trigger do S3: Configure o bucket para disparar a Lambda ao fazer upload de arquivos	
