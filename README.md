# Relatorio-Implementacao-Servicos-AWS
RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 29 de julho de 2025

Cliente: Abstergo Industries Responsável pelo projeto: Sol Morcillo
Objetivo do Projeto

Este relatório apresenta o processo de implementação de três ferramentas da Amazon Web Services (AWS) na empresa Abstergo Industries, com o objetivo de reduzir os custos operacionais de forma imediata, sem comprometer a segurança ou o desempenho da infraestrutura de TI.

# Etapas do Projeto

## 1. Nome da ferramenta: Amazon VPC (Virtual Private Cloud)
   
•	Foco da ferramenta: Estruturação e isolamento de rede na nuvem

•	Descrição de caso de uso: Foi criada uma VPC personalizada com sub-redes públicas para servidores web e sub-redes privadas para bancos de dados e aplicações internas. A configuração permitiu segmentar a arquitetura, reduzindo a exposição de dados sensíveis e eliminando gastos com infraestrutura física de rede.

## 2. Nome da ferramenta: Security Groups
   
•	Foco da ferramenta: Controle de tráfego de rede em nível de instância

•	Descrição de caso de uso: Foram aplicados grupos de segurança com regras personalizadas em instâncias EC2, permitindo apenas o tráfego necessário por protocolo e porta. Isso substituiu firewalls físicos e soluções de segurança terceirizadas, diminuindo custos com licenças e manutenção de software externo.

## 3. Nome da ferramenta: VPC Endpoints
   
•	Foco da ferramenta: Conectividade privada com serviços AWS (como S3 e DynamoDB)

•	Descrição de caso de uso: As instâncias em sub-redes privadas passaram a acessar serviços da AWS diretamente, sem utilizar a internet pública. Isso otimizou a segurança, reduziu a latência e evitou despesas com NAT Gateways e largura de banda pública, gerando economia imediata.

# Impactos Financeiros e Estratégicos

## Impactos Financeiros

•	Redução de custos com infraestrutura física ao migrar para uma rede virtual com Amazon VPC.

•	Eliminação de gastos com firewalls externos ao utilizar Security Groups nativos da AWS.

•	Economia com largura de banda pública e NAT Gateways ao adotar VPC Endpoints para comunicação privada.

## Impactos Estratégicos

•	Maior segurança e controle de tráfego com segmentação de rede e regras personalizadas.

•	Escalabilidade e flexibilidade para adaptar a arquitetura conforme o crescimento da empresa.

•	Melhoria na performance e confiabilidade ao utilizar serviços internos da AWS com baixa latência.

