# Projeto 2 – Perspectiva em Ciência de Dados

![Foto Palmeiras](4.Imagens/palmeiras.jpg)

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

Será aplicada a metodologia de **Conformal Prediction** para o TabICL, permitindo gerar **intervalos de previsão**, em vez de apenas previsões pontuais.

Essa abordagem fornece estimativas mais robustas e informativas, possibilitando:

* Quantificar a incerteza associada às previsões;
* Obter intervalos com garantias estatísticas de cobertura;
* Aumentar a confiabilidade das previsões realizadas.

---

# Interpretabilidade

Para compreender os fatores que mais influenciam as previsões realizadas pelos modelos, serão aplicadas técnicas de interpretabilidade, permitindo analisar como cada variável contribui para os resultados obtidos.

Para os modelos tradicionais, serão avaliadas técnicas de interpretação adequadas às suas características, enquanto para modelos mais complexos será utilizada uma abordagem baseada em explicações locais.

Em especial, será utilizado o método:

* **LIME (Local Interpretable Model-Agnostic Explanations)**

O LIME será aplicado ao modelo **TabICL**, após a etapa de redução de dimensionalidade utilizando **SVD (Singular Value Decomposition)**. Essa etapa é necessária devido à alta dimensionalidade dos dados textuais, permitindo transformar as representações TF-IDF em um conjunto reduzido de componentes mais informativos antes da aplicação do modelo.

A utilização do LIME permitirá:

* Identificar quais características possuem maior influência nas previsões individuais;
* Compreender o comportamento do modelo em diferentes exemplos de notícias;
* Gerar interpretações mais transparentes para modelos complexos de Machine Learning.

---

# Objetivo Geral do Trabalho

O objetivo deste projeto não se limita apenas à identificação do modelo com maior desempenho preditivo.

A proposta principal é realizar uma análise comparativa entre diferentes técnicas de modelagem, explorando desde métodos tradicionais até abordagens mais recentes de Machine Learning.

Dessa forma, busca-se compreender:

* Como diferentes algoritmos se comportam diante do problema de previsão de audiência de notícias;
* As vantagens e limitações de cada abordagem;
* O impacto das diferentes técnicas de representação e processamento dos dados;
* A relação entre desempenho preditivo, interpretabilidade e confiabilidade das previsões.

Além da comparação entre modelos, a aplicação de **Conformal Prediction** e de técnicas de **interpretabilidade** permite uma análise mais completa, considerando não apenas a capacidade preditiva dos modelos, mas também a incerteza associada aos resultados e a compreensão dos fatores que influenciam as decisões realizadas.
```
