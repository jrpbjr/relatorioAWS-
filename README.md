# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 28/01/2026

Empresa: Abstergo Industries 

Responsável pelo relatório: Jose Roberto   

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa farmaceutica ficticia Abstergo Industries, realizado por Jose Roberto. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 2 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- AWS Lambda + ECS
- Otimização de custos, automação e escalonamento de contêineres.
- A Abstergo pode implementar uma solução que utilize o AWS Lambda para monitorar a carga de trabalho do Amazon ECS e escalar automaticamente o número de contêineres em execução com base na demanda. O Lambda pode ser configurado para verificar regularmente a utilização de recursos do ECS (por exemplo, CPU, memória, número de contêineres em execução) e ajustar dinamicamente o número de tarefas ou serviços ECS conforme necessário. Garantindo que esteja usando apenas os recursos necessários a qualquer momento, o que pode resultar em economia de custos significativa, especialmente em cargas de trabalho com variações de demanda ao longo do tempo.
Essa abordagem proporciona um ambiente altamente adaptável, no qual a infraestrutura é escalada dinamicamente com base nas necessidades reais, evitando assim a alocação excessiva de recursos e os custos associados.

Etapa 2: 
- Amazon CloudWatch
- Monitoramento e observabilidade.
- A Abstergo pode utilizar o Amazon CloudWatch para coletar dados de monitoramento e métricas do Amazon ECS, como utilização de CPU, memória e logs de contêineres. O Lambda pode então ser configurado para processar esses dados, analisá-los em busca de padrões e tendências, e tomar decisões automatizadas com base nessas informações. Com base nessa análise, o Lambda pode decidir se deve ajustar automaticamente a capacidade do ECS para lidar com a demanda ou se é apenas uma anomalia temporária que não requer ação. 
Além disso, o CloudWatch também pode ser usado para monitorar o desempenho e a disponibilidade dos serviços ECS, permitindo que a Abstergo identifique e resolva problemas rapidamente antes que afetem negativamente os custos ou a experiência do usuário.

Etapa 3:
- Amazon S3 + Classes de Armazenamento (Lifecycle + Intelligent-Tiering)
- Otimização de custos com armazenamento de dados
- A Abstergo Industries pode utilizar o Amazon S3 como solução de armazenamento de objetos para dados corporativos, como documentos, relatórios, logs históricos, backups e arquivos de pesquisa clínica. Considerando que grande parte desses dados não é acessada com frequência, a empresa pode obter uma redução significativa de custos ao utilizar as classes de armazenamento do S3, como S3 Intelligent-Tiering, S3 Standard-Infrequent Access e S3 Glacier.
Essa abordagem permite à Abstergo reduzir gastos com armazenamento de longo prazo, mantendo alta durabilidade e disponibilidade dos dados, além de eliminar custos desnecessários com armazenamento em classes mais caras quando não há necessidade de acesso frequente.

## Conclusão
Em resumo, a combinação do Lambda, ECS e CloudWatch oferece à Abstergo uma maneira poderosa de otimizar sua infraestrutura na nuvem, automatizando processos, escalonando recursos conforme necessário e monitorando continuamente o desempenho do sistema. Isso não apenas melhora a eficiência operacional, mas também pode levar a uma redução significativa nos custos operacionais e de infraestrutura.

A implementação de ferramentas na empresa Abstergo Industries tem como esperado Escalonamento Dinâmico de Recursos, Automatização de Tarefas Operacionais e Otimização de Desempenho e Uso de Recursos, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa. 


Assinatura do Responsável pelo Projeto: Jose Roberto

Jose Roberto. 
