# Machine Learning (INF01017)

Este repositório contém dois notebooks (`.ipynb`) feitos durante a disciplina de machine learning que abordam diferentes problemas de análise de dados e aplicação de métodos de aprendizado de máquina.

## Índice

1. [Previsão de Gênero Musical no Spotify](#previsão-de-gênero-musical-no-spotify)
2. [Segmentação de Clientes para Crédito Bancário](#segmentação-de-clientes-para-crédito-bancário)

---

## Previsão de Gênero Musical no Spotify

### Descrição

Este notebook visa desenvolver métodos de aprendizado de máquina para prever o gênero de músicas do Spotify com base em diversos atributos. O dataset contém 30.000 registros de músicas, e o objetivo é utilizar três métodos de aprendizado de máquina para classificar o gênero musical: Árvores de Decisão, Naive Bayes e Redes Neurais.

### Ações no Notebook
- O conjunto de dados é carregado e filtrado para selecionar os atributos relevantes.
- É feita uma análise da quantidade de classes e a distribuição dos dados entre as classes.
- São aplicados métodos de aprendizado de máquina para prever o gênero das músicas.

### Métodos Utilizados
- Árvores de Decisão
- Naive Bayes
- Redes Neurais

---

## Segmentação de Clientes para Crédito Bancário

### Descrição

Este notebook tem como objetivo realizar a segmentação de clientes que solicitaram crédito bancário, utilizando um conjunto de dados adaptado de um problema de classificação de risco de crédito. O conjunto de dados não possui rótulos (classes) e inclui um subconjunto de atributos para descrever as instâncias. O objetivo é separar os clientes em grupos (clusters) baseados em características comuns entre eles.

### Ações no Notebook
- O conjunto de dados é analisado e pré-processado.
- São aplicados métodos de segmentação (como o algoritmo de clustering) para agrupar os clientes.
- A segmentação permite a criação de perfis de clientes (personas), ajudando a empresa a oferecer uma comunicação mais assertiva e personalizada.

### Método Utilizado
- Segmentação com base em Clustering (algoritmo K-Means, DBSCAN, etc.)

---
