Português

# Projeto: Clusterização de Clientes em Campanhas de Marketing

## Introdução

Bem-vindo ao projeto de Clusterização de Clientes em Campanhas de Marketing! Este projeto tem como objetivo segmentar os clientes com base em seu comportamento de compra e outras características demográficas, utilizando técnicas de clusterização. Através da análise desses clusters, buscamos entender melhor o perfil dos clientes e otimizar estratégias de marketing direcionadas.


## Objetivos

1. Segmentação de Clientes (Clusterização): Utilizar o algoritmo KMeans para segmentar os clientes em clusters distintos, com base em seu comportamento de compra e características demográficas.
2. Avaliação de Desempenho da Clusterização: Utilizar métricas como silhouette, Davies Bouldin e Calinski para avaliar o desempenho da clusterização e determinar o número ideal de clusters.
3. Análise dos Clusters: Analisar os clusters resultantes para entender os diferentes perfis de clientes e identificar padrões de comportamento de compra.
4. Insights para Estratégias de Marketing: Utilizar os insights obtidos da análise dos clusters para direcionar estratégias de marketing mais eficazes e personalizadas.

## Bibliotecas Utilizadas

- Pandas: Para manipulação e análise eficiente dos dados.
- Scikit-learn: Para implementar o algoritmo KMeans e realizar a clusterização.
- Scikit-learn.preprocessing: Para normalização dos dados.
- Scikit-learn.metrics: Para avaliação do desempenho da clusterização.

## Dados Utilizados

Os dados utilizados neste projeto consistem em um dataframe de clientes com as seguintes colunas:

- 'ID', 'Year_Birth', 'Education', 'Marital_Status', 'Income', 'Kidhome', 'Teenhome', 'Dt_Customer', 'Recency', 'MntWines', 'MntFruits', 'MntMeatProducts', 'MntFishProducts', 'MntSweetProducts', 'MntGoldProds', 'NumDealsPurchases', 'NumWebPurchases', 'NumCatalogPurchases', 'NumStorePurchases', 'NumWebVisitsMonth', 'AcceptedCmp3', 'AcceptedCmp4', 'AcceptedCmp5', 'AcceptedCmp1', 'AcceptedCmp2', 'Complain', 'Z_CostContact', 'Z_Revenue', 'Response'

## Tratamento de Dados

1. Remoção de Colunas: As colunas "ID" e "Dt_Customer" foram removidas do dataframe, pois não contribuem para a análise de clusterização.
2. Tratamento de Dados Faltantes: Foram identificados 24 dados faltantes na coluna "Income". Esses valores foram substituídos pela mediana da coluna.
3. Codificação de Variáveis Categóricas: As variáveis categóricas "Education" e "Marital_Status" foram codificadas utilizando a técnica de one-hot encoding para que pudessem ser utilizadas pelo algoritmo de clusterização.
4. Normalização de Dados: Os dados foram normalizados para garantir que todas as características contribuam igualmente para a clusterização.

## Conclusão

Este projeto de clusterização de clientes em campanhas de marketing visa fornecer insights valiosos para estratégias de marketing mais eficazes e personalizadas. Ao segmentar os clientes em clusters distintos e analisar seus comportamentos de compra, podemos entender melhor suas preferências e necessidades, permitindo-nos direcionar campanhas de marketing de forma mais precisa e direcionada.

Contribuições e Feedback

Se você deseja contribuir ou fornecer feedback, fique à vontade para abrir issues ou pull requests. Sua participação é bem-vinda

-------------------------------------------------------------------------------------------------------------------------

English: 

# Project: Customer Clustering in Marketing Campaigns

## Introduction

Welcome to the Customer Clustering in Marketing Campaigns project! This project aims to segment customers based on their purchasing behavior and other demographic characteristics using clustering techniques. Through the analysis of these clusters, we seek to better understand the customer profile and optimize targeted marketing strategies.

## Objectives

1. Customer Segmentation (Clustering): Utilize the KMeans algorithm to segment customers into distinct clusters based on their purchasing behavior and demographic characteristics.
2. Clusterization Performance Evaluation: Utilize metrics such as silhouette, Davies Bouldin, and Calinski to evaluate the performance of the clustering and determine the optimal number of clusters.
3. Cluster Analysis: Analyze the resulting clusters to understand the different customer profiles and identify patterns in purchasing behavior.
4. Insights for Marketing Strategies: Utilize insights obtained from cluster analysis to direct more effective and personalized marketing strategies.

## Libraries Used

- Pandas: For efficient data manipulation and analysis.
- Scikit-learn: To implement the KMeans algorithm and perform clustering.
- Scikit-learn.preprocessing: For data normalization.
- Scikit-learn.metrics: For evaluating clustering performance.

## Data Used

The data used in this project consists of a customer dataframe with the following columns:

- 'ID', 'Year_Birth', 'Education', 'Marital_Status', 'Income', 'Kidhome', 'Teenhome', 'Dt_Customer', 'Recency', 'MntWines', 'MntFruits', 'MntMeatProducts', 'MntFishProducts', 'MntSweetProducts', 'MntGoldProds', 'NumDealsPurchases', 'NumWebPurchases', 'NumCatalogPurchases', 'NumStorePurchases', 'NumWebVisitsMonth', 'AcceptedCmp3', 'AcceptedCmp4', 'AcceptedCmp5', 'AcceptedCmp1', 'AcceptedCmp2', 'Complain', 'Z_CostContact', 'Z_Revenue', 'Response'

## Data Preprocessing

1. Column Removal: The "ID" and "Dt_Customer" columns were removed from the dataframe as they do not contribute to the clustering analysis.
2. Missing Data Treatment: 24 missing values were identified in the "Income" column. These values were replaced with the median of the column.
3. Encoding Categorical Variables: The categorical variables "Education" and "Marital_Status" were encoded using the one-hot encoding technique to be used by the clustering algorithm.
4. Data Normalization: The data was normalized to ensure that all features contribute equally to clustering.

## Conclusion

This customer clustering project in marketing campaigns aims to provide valuable insights for more effective and personalized marketing strategies. By segmenting customers into distinct clusters and analyzing their purchasing behaviors, we can better understand their preferences and needs, allowing us to direct marketing campaigns more accurately and effectively.

Contributions and Feedback

If you wish to contribute or provide feedback, feel free to open issues or pull requests. Your participation is welcome!
