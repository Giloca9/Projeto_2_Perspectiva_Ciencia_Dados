# Projeto 2 – Perspectiva em Ciência de Dados

![Imagens/palmeiras.jpg]

Este repositório contém o **Projeto 2** desenvolvido para a disciplina de **Perspectiva em Ciência de Dados**.

---

# Contexto

No **Projeto 1**, foram aplicadas técnicas de:

* **Web Scraping**
* **Processamento de Linguagem Natural (NLP)**
* **Análise Exploratória de Dados**

com o objetivo de analisar notícias relacionadas ao **Palmeiras** e desenvolver um modelo preditivo inicial capaz de classificar se uma notícia apresentaria **alta** ou **baixa audiência**.

Como resultado dessa etapa, foram construídas bases de dados contendo representações textuais por meio de técnicas como:

* **Bag of Words (BoW)**
* **TF-IDF**

Além disso, foi consolidado o conjunto de notícias utilizado nas análises e modelagens posteriores.

---

# Proposta do Projeto 2

O **Projeto 2** tem como objetivo dar continuidade ao desenvolvimento do modelo preditivo, ampliando sua capacidade analítica.

Portando continuamos abordando um problema de classificação, cujo principal objetivo é:

> ## Classificar se a notícia terá baixa ou alta audiência

---

# Modelos Avaliados

Serão investigados modelos com diferentes níveis de complexidade, desde abordagens tradicionais até métodos mais modernos de Machine Learning:

* **Regressão Linear**
* **Random Forest**
* **TabPFN / TabICL** 

Os modelos serão comparados utilizando métricas apropriadas para problemas de regressão, permitindo identificar a abordagem com maior capacidade preditiva.

---

# Avaliação dos Modelos

O desempenho dos modelos será avaliado por meio de métricas como:

* **Acurácia**
* **Precisão**
* **Recall**
* **F1-Score**
* **ROC-AUC**

A comparação entre os modelos permitirá selecionar aquele com melhor capacidade preditiva.

---

# Conformal Prediction

Após a seleção do modelo final, será aplicada a metodologia de **Conformal Prediction**, permitindo gerar **intervalos de previsão**, em vez de apenas previsões pontuais.

Essa abordagem fornece estimativas mais robustas e informativas, possibilitando:

* Quantificar a incerteza associada às previsões;
* Obter intervalos com garantias estatísticas de cobertura;
* Aumentar a confiabilidade das previsões realizadas.

---

# Interpretabilidade

Para compreender os fatores que mais influenciam as previsões, serão aplicadas técnicas de interpretabilidade de modelos, com destaque para:

* **SHAP (SHapley Additive exPlanations)**

Essas técnicas permitirão:

* Identificar as variáveis mais importantes;
* Compreender a contribuição individual de cada característica;
* Extrair insights relevantes sobre os fatores que impactam a audiência das notícias relacionadas ao Palmeiras.

---

