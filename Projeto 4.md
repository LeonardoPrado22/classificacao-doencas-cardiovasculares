# Projeto 4 — Classificação Preditiva de Doenças Cardiovasculares

---

## 📚 Explicação do Curso
Este projeto foi desenvolvido como parte do curso de Cientista de Dados da EBAC, focando no modelo fundamental de **classificação binária** e na sua **interpretabilidade** em um contexto de saúde. O objetivo é construir um modelo capaz de prever doenças cardiovasculares, utilizando dados históricos reais de pacientes.

---

## 🎯 Objetivos
O principal objetivo deste projeto é a consolidação das habilidades de Machine Learning com foco na Regressão Logística:

* **Implementação da Regressão Logística:** Aplicar o algoritmo para um problema de classificação binária (previsão de doença cardíaca: Sim/Não).
* **Pré-processamento e Padronização:** Realizar o tratamento de dados (faltantes e outliers) e a padronização das *features* (idade, peso, etc.) para otimizar o desempenho do modelo.
* **Análise de Risco:** Analisar e interpretar as métricas de classificação, como Acurácia, **Recall** e **ROC AUC**, que são fundamentais para cenários onde o custo do erro de classificação é alto.
* **Interpretabilidade:** Consolidar o entendimento da Regressão Logística como um classificador preditivo de alta interpretabilidade em um domínio clínico.

---

## 💻 Tecnologias Usadas
* **Linguagem:** Python
* **Algoritmo Principal:** Regressão Logística.
* **Bibliotecas Principais:** Pandas, NumPy, Scikit-learn, Matplotlib e Seaborn.
* **Pré-processamento:** `StandardScaler` (Padronização).
* **Ambiente:** Jupyter Notebook.

---

## 📈 Principais Análises Realizadas
O projeto focou nas seguintes etapas e análises técnicas:

* **Pré-processamento e Padronização:** Tratamento inicial da base, incluindo a checagem de tipos de dados e a padronização dos dados de saúde (como idade e peso) para otimizar o desempenho do modelo.
* **Análise Bivariada Exploratória:** Exploração do comportamento da variável *target* (`cardio_disease`) com outras variáveis como gênero, peso e altura, extraindo *insights* visuais sobre a correlação.
* **Modelagem Preditiva:** Treinamento do modelo de classificação para prever o risco de doenças cardiovasculares com base em variáveis clínicas (tabagismo, colesterol, atividade física, etc.).
* **Avaliação de Risco:** Cálculo da **Matriz de Confusão** e do *Classification Report*, detalhando Falsos Positivos e Falsos Negativos.
* **Validação do Classificador:** Interpretação da **Curva ROC AUC**, confirmando a capacidade do modelo de distinguir de forma robusta entre as classes (doentes/não doentes).

---

## ✨ Insights Chave (Valor de Negócio e Conclusão)

As conclusões extraídas deste modelo são essenciais para a aplicação clínica:

* **Interpretabilidade Clínica:** A **Regressão Logística** foi validada como um modelo eficaz e de alta interpretabilidade. Sua natureza linear facilita a compreensão da influência de cada fator de risco (como idade ou tabagismo) no diagnóstico, o que é crucial para a validação médica.
* **Foco na Segurança:** A análise de métricas como o **Recall** é fundamental, pois o modelo foi ajustado para minimizar o **Falso Negativo** (o custo de não diagnosticar um paciente doente é clinicamente mais alto).
* **Ferramenta de Alerta Precoce:** O modelo é capaz de processar dados clínicos e indicar se novos pacientes estão propensos a doenças cardiovasculares, servindo como uma ferramenta de triagem e alerta precoce para a equipe de saúde.