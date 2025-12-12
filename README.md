# 🤖 DataOps para a Nova Era: Integração Híbrida de Agentes de IA e ML Clássico


### Visão Geral do Projeto e Desafio CBL


> Este repositório implementa um *pipeline* de Machine Learning e Agentes de IA projetado para **otimizar a tomada de decisão de retenção de clientes**,
> focando na **sustentabilidade de custos (FinOps)** e **transparência (Auditabilidade Git)**.
>
> **💡 Desafio Principal (CBL):** Reduzir o custo operacional da inferência em 30% ao rotear decisões para o ML Clássico,
> ativando Agentes de IA (LLMs) apenas para casos de alto valor.

### Arquitetura Híbrida e Fluxo de Decisão


Explique o fluxo de trabalho discutido (**Roteamento Inteligente**).

> A arquitetura é baseada em um modelo **híbrido**, onde o **Agente de IA** (LLM) atua como camada de raciocínio, e o **ML Clássico** (XGBoost/LogReg) atua como motor de previsão de baixo custo.
>
> 
> 

### Pilares de Sustentação (Tecnologia e Governança)

Esta seção mapeia os principais conceitos para as ferramentas utilizadas.

| Pilar | Propósito | Ferramentas Chave |
| :--- | :--- | :--- |
| **DataOps & Clean Code** | Tratar o gargalo de *features* em dados tabulares e garantir a robustez do pré-processamento. | **Skrub (TableVectorizer)**, Pandas, SQL. |
| **Interpretabilidade** | Transformar a previsão em *insight* acionável e transparente para o Agente de IA. | **SHAP** (SHapley Additive exPlanations). |
| **Governança & Sustentabilidade** | Monitorar e otimizar os custos de inferência de LLMs e garantir o ROI. | **FinOps** (Métricas de Custo), Roteamento Híbrido. |
| **Auditabilidade** | Vincular cada versão do modelo e do dado ao código-fonte. | **Git (Hash de Commit)**, Metadados de Inferência. |

### Setup e Execução (Para Auditabilidade)

Instruções claras para configurar o ambiente e reproduzir os resultados, essenciais para a **Auditabilidade Git**.

