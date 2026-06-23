# Projeto 2 - Perspectiva Ciencia Dados

Este repositório contém o Projeto 2 desenvolvido para a disciplina de Perspectiva em Ciência de Dados. 

## Contexto 
No Projeto 1 foram aplicadas técnicas de Web Scraping, Processamento de Linguagem Natural (NLP) e Análise Exploratória de Dados em notícias relacionadas ao Palmeiras. Além disso, foi desenvolvido um modelo preditivo inicial com o objetivo de classificar se uma notícia apresentaria alta ou baixa audiência.

Como resultado dessa etapa, foram construídas bases de dados contendo representações textuais por meio de técnicas como Bag of Words (BoW) e TF-IDF, além da consolidação do conjunto de notícias utilizadas nas análises.

## Proposta Projeto 2

O Projeto 2 tem como objetivo dar continuidade ao desenvolvimento do modelo preditivo, ampliando sua capacidade analítica. Em vez de realizar apenas uma classificação de audiência, o foco será prever o número de visitas que uma notícia poderá receber, caracterizando um problema de regressão.

Para isso, serão avaliadas técnicas mais robustas e modernas de Machine Learning, como XGBoost, LightGBM e TabPFN/TabICL (ajustar conforme o método escolhido), comparando seus desempenhos com o modelo desenvolvido anteriormente. A avaliação será realizada por meio de métricas apropriadas para regressão, permitindo identificar o modelo com maior capacidade preditiva.

Após a seleção do melhor modelo, será aplicada a metodologia de Conformal Prediction, possibilitando a geração de intervalos de previsão em vez de valores pontuais. Essa abordagem fornece estimativas mais informativas e confiáveis, uma vez que expressa a incerteza associada às previsões e indica uma faixa provável para o número de visitas da notícia.

Por fim, serão empregadas técnicas de interpretabilidade de modelos, com destaque para o SHAP (SHapley Additive exPlanations), permitindo compreender quais características exercem maior influência sobre as previsões realizadas. Dessa forma, além de obter um modelo com elevada capacidade preditiva, será possível extrair insights relevantes sobre os fatores que impactam a audiência das notícias relacionadas ao Palmeiras.