# Modelos de Previsão de Visitas

Esta pasta contém os notebooks utilizados na etapa de modelagem do projeto. O objetivo geral é prever quais notícias tendem a ter maior número de visitas, usando como base os textos das notícias coletadas.



## Arquivos da pasta

### `log\_rf.ipynb`

Notebook principal de modelagem com algoritmos clássicos de Machine Learning.

Neste arquivo são realizadas as seguintes etapas:

* carregamento e preparação da base de notícias;
* criação da variável resposta `hot`, que identifica as notícias entre as 20% mais acessadas;
* análise exploratória inicial da distribuição de visitas;
* divisão dos dados em treino, validação e teste;
* transformação dos textos com TF-IDF;
* treinamento e avaliação de modelos de Regressão Logística;
* treinamento e avaliação de modelos de Random Forest;
* comparação dos resultados por métricas como acurácia, precisão, recall, F1-score, ROC-AUC e matriz de confusão.

Esse notebook serve como referência principal para avaliar o desempenho dos modelos tradicionais na tarefa de classificação das notícias.

### `tabicl (2).ipynb`

Notebook complementar com aplicação do modelo **TabICL**.

Neste arquivo, o objetivo é testar uma abordagem alternativa de classificação utilizando In-Context Learning para dados tabulares. Como os textos são transformados em variáveis numéricas, o notebook utiliza:

* vetorização dos textos com TF-IDF;
* redução de dimensionalidade com Truncated SVD;
* treinamento do TabICL para classificação binária;
* avaliação do modelo no conjunto de teste;
* geração de probabilidades de classificação;
* aplicação de conjuntos de predição para analisar a confiança das classificações;
* interpretação dos componentes gerados a partir da transformação dos textos.

Esse notebook complementa a análise dos modelos tradicionais, permitindo comparar uma abordagem mais recente com os métodos clássicos.

## Como executar

1. Abrir o notebook desejado.
2. Executar as células em sequência.
3. As bases utilizadas já estão disponíveis dentro do repositório, não sendo necessário baixar arquivos externos.

Caso o notebook seja executado fora da estrutura original do projeto, pode ser necessário ajustar apenas o caminho de leitura da base de dados.

