# Google-advanced-data-analytics-projects

# Initial Data Inspection - Waze User Churn Project

## Project Overview
This project is part of the **Google Advanced Data Analytics Professional Certificate**. The primary goal is to simulate a real-world scenario within the Waze data team, focused on developing a Machine Learning model to predict user churn (when users stop using the app).

In this initial phase, the focus was on data ingestion, inspection, and preliminary cleaning to ensure the dataset is ready for Exploratory Data Analysis (EDA) and future modeling.

## Objectives
* Import and structure the Waze user dataset using Python.
* Assess data integrity, including data types and DataFrame dimensions.
* Identify and isolate missing values for future treatment.
* Perform basic descriptive statistics to understand the distribution of variables.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy
* **Environment:** Jupyter Notebook

## Key Insights
During the data inspection phase, several critical points were identified:
1.  **Missing Values:** The `label` column (the target variable for churn prediction) contains exactly **700 missing values**. All other features are fully populated.
2.  **Device Distribution:** A preliminary analysis shows that the ratio of iPhone to Android users is nearly identical across both "Churned" and "Retained" groups (approximately 64% iPhone / 35% Android).
3.  **Statistical Consistency:** The descriptive statistics for the group with missing labels showed no major anomalies when compared to the full dataset, which will inform future decisions regarding data imputation or removal.

## Next Steps
With the data cleaned and initial anomalies identified, the project will move into the **Exploratory Data Analysis (EDA)** phase, focusing on data visualization and correlation analysis to identify the key drivers of user churn.

###############################################################################################################################################################################################################################

# Versão em Português:
# Análise Exploratória Inicial - Dados de Usuários Waze

## Contexto do Projeto
Este projeto faz parte do portfólio construído durante a certificação em Data Analytics. O objetivo simula um cenário real dentro da equipe de dados do aplicativo Waze, que está desenvolvendo um modelo de Machine Learning para prever o *churn* (abandono do aplicativo) de usuários. 

Nesta etapa inicial, a missão foi realizar a importação, inspeção e limpeza preliminar dos dados para garantir que a base esteja pronta para a Análise Exploratória de Dados (EDA) e futuras visualizações.

## Objetivos
* Importar e estruturar o dataset de usuários usando Python.
* Avaliar a integridade dos dados, tipos de variáveis e dimensões do DataFrame.
* Identificar e isolar valores nulos (missing values) para tratamento adequado.
* Analisar estatísticas descritivas básicas das variáveis contínuas.

## Ferramentas e Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** Pandas, NumPy
* **Ambiente:** Jupyter Notebook

## Principais Descobertas
Durante a inspeção dos dados, os seguintes pontos foram mapeados:
1. **Valores Ausentes:** Identificou-se que a coluna `label` (variável alvo para predição de churn) possui exatos **700 valores nulos**. As demais variáveis estão 100% preenchidas.
2. **Proporção de Dispositivos:** Uma análise preliminar revelou que a proporção de usuários de iPhone e Android é muito semelhante tanto no grupo que abandonou o app (Churned) quanto no grupo que permaneceu (Retained), girando em torno de 64% para iPhone e 35% para Android em ambos os casos.
3. **Distribuição Consistente:** As estatísticas descritivas do grupo com a coluna `label` ausente não apresentaram anomalias graves quando comparadas com as estatísticas do dataset completo, o que guiará as próximas decisões de imputação ou exclusão dessas linhas.

## Próximos Passos
Com os dados limpos e as anomalias identificadas, o projeto avançará para a fase de Análise Exploratória de Dados (EDA) aprofundada, com foco em visualização de dados e correlação de variáveis para entender os gatilhos que levam ao abandono do aplicativo.
