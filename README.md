# ELT_Ecommerce
Projeto guiado pela Imersao da Jornada de Dados
Tratamento de dados de um arquivo csv, tendo todo o ELT até um agente de IA n8n
# 📊 ELT_Ecommerce

Projeto guiado pela **Imersão da Jornada de Dados** — uma **pipeline de dados ELT** para processar, transformar e analisar dados de e-commerce.

---

## 🧠 Sobre o projeto

Este projeto implementa um fluxo de dados no modelo **ELT (Extract, Load, Transform)** — onde os dados são:

1. **Extraídos** de fontes (CSV, Parquet ou bases de dados),
2. **Carregados** em um destino persistido,
3. **Transformados** após o carregamento para análises e relatórios. :contentReference[oaicite:1]{index=1}

A finalidade é demonstrar um pipeline real de dados de e-commerce, com foco em organização, preparação e transformação para consumo analítico.

---

## 🛠 Tecnologias

O projeto combina algumas das principais ferramentas e linguagens usadas em engenharia de dados:

| Categoria | Tecnologias sugeridas |
|-----------|------------------------|
| Linguagem | Python, Jupyter Notebook |
| Pipelines | ELT, Orquestração (ex.: n8n, Airflow) |
| Transformação | dbt (Data Build Tool) |
| Armazenamento | arquivos CSV/Parquet ou banco de dados relacional |
| Visualização | (opcional) ferramentas de dashboard / BI |

> **Nota:** adapte as ferramentas conforme seu ambiente e preferências.

---

## 📂 Estrutura do repositório

```text
ELT_Ecommerce
├── Data/                      # Dados brutos (CSV, Parquet, etc)
├── Python/                    # Scripts de extração ou carga
├── Workflow_n8n/              # (Opcional) Workflows de automação
├── dbtcloud/                  # Transformações dbt
├── README.md
├── LICENSE
└── arquivos de dados (.csv)
