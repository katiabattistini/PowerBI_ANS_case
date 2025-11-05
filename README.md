# 📊 [Power BI] Análise de Operadoras de Planos de Saúde (ANS)

![Badge de Status do Projeto - Exemplo](https://img.shields.io/badge/Status-Concluído-success)

Este repositório contém um projeto de Business Intelligence desenvolvido em **Power BI** para analisar dados abertos da Agência Nacional de Saúde Suplementar (ANS). O objetivo principal é fornecer *insights* sobre o mercado de operadoras, focando em sua situação cadastral (Ativas/Canceladas) e na performance de atendimento ao beneficiário (Reclamações).

---

## 🎯 Objetivos do Case

O projeto foi estruturado para atender a dois objetivos de negócio principais:

### Objetivo 1: Situação Cadastral das Operadoras

* Criar um painel de controle para visualizar o status das operadoras.
* **Métricas Chave:** Total de Operadoras Ativas, Total de Operadoras Canceladas  e Total Geral de Operadoras(apresentadas em Cards).
* **Detalhes:** Lista contendo o **Registro ANS**, **Razão Social** , **UF** e **Status** de cada operadora.
* **Interatividade:** Filtro para seleção de Operadoras Ativas e/ou Canceladas.
* **Diferencial:** Mapa do Brasil com gradiente de cores de quantidade de operadoras por UFC.

### Objetivo 2: Análise de Reclamações de Beneficiários

* Identificar as operadoras com maior volume de reclamações no estado de São Paulo.
* **Métricas Chave:** Lista de quantidade de Reclamações por Operadora e por UF de Atendimento. Total de Reclamações (apresentada em card)
* **Visualização Principal:** Top 10 operadoras com mais reclamações no estado de **São Paulo (SP)**.
* **Detalhes:** Ranking de assuntos de reclamações e Ranking de reclamações por UF.
* **Interatividade:** Filtro para seleção de UF.
---

## 📁 Estrutura do Repositório

| Arquivo/Pasta | Descrição |
| :--- | :--- |
| `[case_katia_battistini].pbix` | O arquivo principal do Power BI contendo o modelo de dados, ETL (Power Query) e visualizações. |
| `/Dados_Originais/` | Pasta contendo as fontes de dados brutas utilizadas no projeto. |
| `operadoras_ativas.csv/xls` | Dados das Operadoras Ativas da ANS. |
| `operadoras_canceladas.csv/xls` | Dados das Operadoras Canceladas da ANS. |
| `dicionario_de_dados_das_operadoras_ativas*.xls` | Dicionários de dados das operadoras ativas fornecidos pela ANS. |
| `Dicionario_de_dados_das_operadoras_canceladas*.xls` | Dicionários de dados das operadoras canceladas fornecidos pela ANS. |
| `dicionario_de_dados_demandas_de_consumidor*.xls` | Dicionários de dados das reclamações de operadoras  fornecidos pela ANS. |
| `pda-014-demandas_dos_consumidores_reclamacao_beneficiarios-2025.csv/xls` | Dados de Reclamações de Beneficiários para o ano de 2025. |
| `/images/` | Pasta contendo as imagens das páginas do dashboard do Power BI |
| `README.md` | Este arquivo, o manual do projeto. |
---

## 💻 Tecnologias e Fontes de Dados

| Ferramenta / Recurso | Descrição |
| :--- | :--- |
| **Power BI Desktop** | Utilizado para ETL, Modelagem de Dados, DAX e Visualização. |
| **FIGMA** | Utilizado para design de tela de fundo das páginas do Power BI |
| **Fonte de Dados** | Dados Abertos da ANS (Agência Nacional de Saúde Suplementar) e Portal de Dados do Governo Federal. |
| **Chave de Relacionamento** | O campo unificador em todas as tabelas é o `REGISTRO_OPERADORA`. |

### **Links das Fontes de Dados:**

* **Operadoras Ativas:** [https://dados.gov.br/.../operadoras-de-planos-de-saude-ativas](https://dados.gov.br/dados/conjuntos-dados/operadoras-de-planos-de-saude-ativas)
* **Operadoras Canceladas:** [https://dados.gov.br/.../operadoras-de-planos-de-saude-canceladas](https://dados.gov.br/dados/conjuntos-dados/operadoras-de-planos-de-saude-canceladas)
* **Reclamações de Beneficiários:** [https://dados.gov.br/.../demandas-dos-consumidores--reclamacoes-de-beneficiarios](https://dados.gov.br/dados/conjuntos-dados/demandas-dos-consumidores--reclamacoes-de-beneficiarios)

---

## ⚙️ Como Abrir e Visualizar o Painel

1.  **Pré-requisito:** Tenha o **Power BI Desktop** instalado.
2.  **Clonar o Repositório:** Clone este repositório para sua máquina local usando o Git (via VS Code, como fizemos, ou pela linha de comando).
3.  **Abrir o Arquivo:** Abra o arquivo `[case_katia_battistini].pbix` no Power BI Desktop.
4.  **Visualizar:** O painel será carregado, permitindo a interação com os filtros e visuais para explorar as métricas de operadoras e reclamações.

---

## 🖼️ Preview do Dashboard

`![Dashboard Preview](https://github.com/katiabattistini/PowerBI_ANS_case/blob/main/images/painel_operadoras.PNG)`
`![Dashboard Preview](https://github.com/katiabattistini/PowerBI_ANS_case/blob/main/images/painel_reclamacoes.PNG)`
---

## 🙋 Contato

Se tiver dúvidas, sugestões ou quiser discutir o projeto, me encontre no:

* **LinkedIn:** https://www.linkedin.com/in/katiabattistini/
* **GitHub:** https://github.com/katiabattistini