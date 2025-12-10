# Redução dos Custos em Farmácias com AWS
📄 Relatório de Implementação de Serviços AWS: Setor Farmacêutico
Data: 09/12/2025
Empresa: Abstergo Industries
Responsável: Marcelo David Barudi
## 📝 Introdução
Este relatório apresenta o processo de implementação de ferramentas da Amazon Web Services (AWS) na empresa  Abstergo Industries , realizado por Marcelo David Barudi. O objetivo primordial do projeto foi elencar 3 serviços AWS com foco na realização de diminuição de custos imediatos em operações de TI, o que é crucial para otimizar o capital de pesquisa e desenvolvimento (P&D) no setor farmacêutico.
## 🚀 Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma focada em um serviço AWS específico para a redução de custos.
Objetivo Geral: Redução de custos imediatos em infraestrutura de TI, otimização do armazenamento de dados regulatórios e de pesquisa, e melhoria na gestão de recursos de computação.
A seguir, serão descritas as etapas do projeto e os serviços selecionados:

Etapa
Serviço AWS Sugerido
Foco Principal
Ganho Principal (Redução de Custos)

Etapa 1
Amazon S3 (Simple Storage Service)
Armazenamento de Dados de Pesquisa e Regulatórios (Ex: estudos clínicos, genomas)
Substituição de armazenamento on-premises caro e escalabilidade otimizada, usando classes de armazenamento (S3 Infrequent Access, Glacier) para dados menos acessados.

Etapa 2
Amazon EC2 Reserved Instances (RIs)
Otimização da Computação para Análises e Lotes (Ex: simulações moleculares, modelos de IA)
Desconto significativo (até 75%) sobre o custo sob demanda, garantindo capacidade para cargas de trabalho contínuas e previsíveis (como servidores de LIMS ou ambientes de validação).

Etapa 3
AWS Cost Explorer
Governança e Transparência Financeira (FinOps)
Identificação rápida de gastos não otimizados (recursos ociosos), permitindo desligamento imediato ou redimensionamento de instâncias, e previsão de gastos.
Detalhamento das Etapas:

Etapa 1: Amazon S3 (Simple Storage Service)
Nome da ferramenta: Amazon S3 (com foco nas Storage Classes)
Foco da ferramenta: Armazenamento altamente durável e escalável de dados de P&D e conformidade (HIPAA/LGPD/etc.).
Descrição de caso de uso: Migrar grandes volumes de dados de pesquisa (como imagens médicas, sequenciamento genômico ou relatórios de estudos clínicos) de servidores locais para o S3, utilizando a classe S3 Glacier para dados de longo prazo exigidos por regulamentações e a classe S3 Standard-IA para dados acessados ocasionalmente.
Ganho Principal: Redução imediata nos custos de hardware, manutenção e espaço físico, aproveitando o modelo pay-as-you-go e a otimização de custos por meio das classes de armazenamento.

Etapa 2: Amazon EC2 Reserved Instances (RIs)
Nome da ferramenta: Amazon EC2 Reserved Instances
Foco da ferramenta: Redução do custo de computação para workloads previsíveis e contínuos (serviços de laboratório, bancos de dados, aplicações internas).
Descrição de caso de uso: Analisar a utilização histórica das instâncias EC2 que rodam sistemas críticos (ex: LIMS - Laboratory Information Management System ou infraestrutura de validação) e adquirir RIs de 1 ou 3 anos.
Ganho Principal: Descontos substanciais sobre o preço sob demanda, garantindo uma economia imediata e previsível para os recursos de computação que a empresa sabe que precisará.

Etapa 3: AWS Cost Explorer
Nome da ferramenta: AWS Cost Explorer
Foco da ferramenta: Monitoramento, análise e otimização contínua dos gastos da AWS.
Descrição de caso de uso: Configurar o Cost Explorer para rastrear os gastos diários e identificar instâncias (EC2, RDS) ociosas, volumes de armazenamento (EBS) não utilizados ou serviços subutilizados. Criar alertas de orçamento para evitar picos de custos não planejados.
Ganho Principal: Economia ativa e contínua através da visibilidade e da capacidade de tomar ações corretivas rápidas (desligamento ou downsizing de recursos), reforçando a cultura de FinOps.

## ✅ Conclusão

A implementação de ferramentas AWS como S3, EC2 RIs e Cost Explorer na empresa Empresa: Abstergo Industries tem como esperado [redução de gastos de infraestrutura, otimização de capital, agilidade regulatória e governança financeira], o que aumentará a eficiência operacional e a produtividade da empresa (liberando recursos de TI para focar em inovação).

Por que é interessante aplicar estes serviços da AWS no Setor Farmacêutico?
Conformidade e Segurança: A AWS oferece certificações e ferramentas que auxiliam enormemente no cumprimento de rigorosos requisitos regulatórios (como GxP, HIPAA, GDPR/LGPD) necessários para dados de P&D e pacientes.
Escalabilidade para P&D: O setor farmacêutico exige alta capacidade de computação para simulações e análise de Big Data (genômica). A AWS permite escalar esses recursos sob demanda, pagando apenas pelo uso, o que é mais econômico que manter um data center local ocioso.
Foco no Core Business: Ao transferir a gestão da infraestrutura básica para a AWS, a equipe de TI da Empresa: Abstergo Industries pode se concentrar em projetos que geram valor direto, como o desenvolvimento de novos medicamentos.
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias (como o uso de Serverless com AWS Lambda para automação de processos) que possam melhorar ainda mais os processos da empresa.

## 📎 Anexos
[lista de anexos, como manuais de configuração do S3, relatórios de Cost Explorer iniciais, plano de aquisição de RIs, entre outros]
Assinatura do Responsável pelo Projeto:
MARCELO DAVID BARUDI


