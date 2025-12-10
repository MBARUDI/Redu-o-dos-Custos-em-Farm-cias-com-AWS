# 💰 Redução de Custos na Indústria Farmacêutica com AWS

## 📝 Detalhes do Relatório
| Campo | Informação |
| :--- | :--- |
| **Data** | 09/12/2025 |
| **Empresa** | Abstergo Industries |
| **Responsável** | Marcelo David Barudi |
| **Foco** | Diminuição de Custos Imediatos em Operações de TI |

---

## 💡 Introdução
Este relatório detalha a proposta de implementação de serviços da **Amazon Web Services (AWS)** na **Abstergo Industries**. O objetivo principal é elencar e aplicar **3 serviços AWS** com foco direto na **redução de custos imediatos**, permitindo otimizar o capital crucial para Pesquisa e Desenvolvimento (P&D) no setor farmacêutico.

---

## 🚀 Descrição do Projeto: As 3 Etapas de Otimização

O projeto está estruturado em 3 etapas, cada uma focada em um serviço AWS essencial para a economia de recursos.

> **Objetivo Geral:** Redução imediata de custos em infraestrutura, otimização do armazenamento de dados regulatórios e de pesquisa, e melhoria na gestão de recursos de computação.

### Tabela Resumo dos Serviços e Ganhos

| Etapa | Serviço AWS | 🎯 Foco Principal | 💸 Ganho Principal (Redução de Custos) |
| :---: | :--- | :--- | :--- |
| **1** | `Amazon S3` (Simple Storage Service) | Armazenamento de Dados de P&D e Regulatórios | Substituição de armazenamento *on-premises* caro e **escalabilidade otimizada** (uso de S3 IA/Glacier). |
| **2** | `Amazon EC2 Reserved Instances` (RIs) | Otimização da Computação (Análises, Lotes) | **Desconto significativo (até 75%)** sobre o custo sob demanda para cargas de trabalho previsíveis. |
| **3** | `AWS Cost Explorer` | Governança e Transparência Financeira (FinOps) | **Identificação e eliminação rápida de gastos não otimizados** (recursos ociosos) e previsão de gastos. |

---

### Detalhamento das Etapas

#### **1. Amazon S3 (Simple Storage Service)**
* **Nome da Ferramenta:** `Amazon S3` (com foco nas Storage Classes)
* **Foco Principal:** Armazenamento altamente durável e escalável de dados de P&D e conformidade (HIPAA/LGPD/etc.).
* **Caso de Uso:** Migrar grandes volumes de dados de pesquisa (genômica, estudos clínicos) para o S3. Utilização estratégica das classes **S3 Glacier** (longo prazo regulatório) e **S3 Standard-IA** (acesso ocasional).
* **Ganho:** Redução imediata nos custos de *hardware*, manutenção e espaço físico, aproveitando o modelo *pay-as-you-go*.

#### **2. Amazon EC2 Reserved Instances (RIs)**
* **Nome da Ferramenta:** `Amazon EC2 Reserved Instances`
* **Foco Principal:** Redução do custo de computação para *workloads* previsíveis e contínuas (serviços de laboratório, infraestrutura de validação).
* **Caso de Uso:** Analisar a utilização histórica de instâncias que rodam sistemas críticos (e.g., LIMS) e adquirir RIs de 1 ou 3 anos.
* **Ganho:** Descontos substanciais sobre o preço sob demanda, garantindo uma economia imediata e previsível para os recursos base de computação.

#### **3. AWS Cost Explorer**
* **Nome da Ferramenta:** `AWS Cost Explorer`
* **Foco Principal:** Monitoramento, análise e otimização contínua dos gastos da AWS (**FinOps**).
* **Caso de Uso:** Configurar o Cost Explorer para rastrear gastos diários, identificar recursos ociosos (EC2, EBS) e criar alertas de orçamento para evitar picos de custos.
* **Ganho:** Economia ativa e contínua através da visibilidade e da capacidade de tomar ações corretivas rápidas (desligamento ou *downsizing* de recursos).

---

## ✅ Conclusão: Por Que AWS no Setor Farmacêutico?

A implementação dos serviços `S3`, `EC2 RIs` e `Cost Explorer` na **Abstergo Industries** resultará em **redução de gastos de infraestrutura, otimização de capital, agilidade regulatória e governança financeira**.

### Benefícios Chave:
* **🛡️ Conformidade e Segurança:** AWS auxilia no cumprimento de rigorosos requisitos regulatórios (GxP, HIPAA) para dados de P&D e pacientes.
* **📈 Escalabilidade para P&D:** Capacidade de computação sob demanda para simulações e análise de Big Data (genômica), mais econômica do que manter *data centers* locais ociosos.
* **🎯 Foco no Core Business:** A equipe de TI concentra-se em projetos de valor (desenvolvimento de medicamentos) ao invés da gestão da infraestrutura básica.

**Recomendação:** Recomenda-se a continuidade do uso das ferramentas e a exploração de novas tecnologias, como o uso de **Serverless com AWS Lambda**, para automação e maior otimização de custos.

---

## 📎 Anexos
* [Lista de anexos, como manuais de configuração do S3, relatórios de Cost Explorer iniciais, plano de aquisição de RIs, etc.]

**Assinatura do Responsável pelo Projeto:**

> MARCELO DAVID BARUDI


