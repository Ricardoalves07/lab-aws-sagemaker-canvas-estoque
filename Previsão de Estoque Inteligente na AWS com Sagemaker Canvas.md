# Previsão de Estoque usando Machine Learning

Este projeto utiliza o Amazon SageMaker Canvas para criar modelos de previsão de estoque. Abaixo está uma visão geral do projeto.

## Objetivo
Prever a quantidade de estoque necessária para diferentes produtos, utilizando técnicas de Machine Learning.

## Dados
- Dados de vendas históricos.
- Informações sobre promoções, feriados e outras variáveis sazonais.

## Técnicas Utilizadas
- Pré-processamento de dados.
- Treinamento de modelos de regressão.
- Avaliação de modelos usando métricas como MAE e RMSE.

  ## Passo a Passo

### 1. Criação do Dataset

**1.1. Coleta de Dados:**
- peguei uma tabela com dados históricos de vendas, incluindo informações como data, quantidade vendida, preço, promoções, feriados e outras variáveis sazonais.
- Armazenaei os dados em um formato estruturado, CSV.

**1.2. Limpeza e Pré-processamento de Dados:**
- Removi e corrigi valores ausentes ou inconsistentes.
- Normalizei variáveis numéricas.
     ![alt text](Criação do datatasat.png") 

### 2. Construção e Treinamento do Modelo

**2.1. Escolha do Modelo:**

- Escolhi um modelo preditivo
  ![Logo do Markdown](Criação de modelo preditivo.png")
**2.2. Treinamento do Modelo:**
  
- Utilizi os dados de treino para ajustar os modelos escolhidos.
- configurei o modelo de série temporal antes de construí-lo.

**2.3. Ferramentas Utilizadas:**
- Amazon SageMaker Canvas para construção e treinamento do modelo.
- Jupyter Notebooks para análise exploratória de dados e experimentação de modelos.

### 3. Análise do Modelo

**3.1. Avaliação do Modelo:**
- Utilizar métricas como MAE (Mean Absolute Error) e RMSE (Root Mean Squared Error) para avaliar a performance dos modelos.
- Analisar os resíduos das previsões para identificar possíveis padrões ou problemas.

**3.2. Validação do Modelo:**
- Validar o modelo usando o conjunto de teste para garantir que ele generalize bem para dados não vistos.
- Comparar a performance do modelo em diferentes conjuntos de dados para verificar sua robustez.

### 4. Previsões Usando o Modelo

**4.1. Preparação dos Dados para Previsão:**
- Coletar novos dados de entrada, semelhantes aos utilizados no treinamento.
- Pré-processar esses dados da mesma forma que foi feito no conjunto de treino.
- dei um quick buider para fazer uma análise mais rápida dos dados.

**4.2. Geração de Previsões:**
- Utilizei o modelo treinado para gerar previsões de estoque para os novos dados.
- analizei as previsões para tomar decisões informadas sobre o estoque.

**4.3. Implementação das Previsões:**
- Integrar as previsões do modelo em sistemas de gestão de estoque.
- Monitorar continuamente a performance do modelo e atualizá-lo conforme necessário.

## Resultados
Os modelos preditivos foram capazes de prever com precisão as necessidades de estoque.

