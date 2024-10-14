# Análise de Clusters de Compras

Este projeto realiza uma análise de clusters em dados de compras, utilizando técnicas de aprendizado de máquina não supervisionado para identificar padrões nos comportamentos de compra dos clientes.

## Visão Geral

O notebook realiza as seguintes etapas principais:

1. Importação e pré-processamento dos dados
2. Aplicação de três algoritmos de clustering:
   - K-Means
   - Clusterização Hierárquica
   - DBSCAN
3. Visualização dos clusters usando PCA e t-SNE
4. Avaliação dos resultados usando várias métricas
5. Análise detalhada dos clusters identificados

## Requisitos

Para executar este notebook, você precisará das seguintes bibliotecas Python:

- numpy
- pandas
- matplotlib
- scikit-learn
- scipy
- yellowbrick
- feature_engine

Você pode instalar estas dependências usando pip:

```
pip install numpy pandas matplotlib scikit-learn scipy yellowbrick feature_engine
```

## Estrutura do Projeto

O projeto consiste em um notebook Jupyter (`main.ipynb`) que contém todo o código e análise e um arquivo .csv de onde os dados foram retirados.
Esses dados podem ser encontrados também em https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset

## Principais Resultados

A análise identificou dois clusters principais de clientes:

1. **Cluster 0**:
   - Perfil de Compra: Compra menos frequentemente
   - Gênero: 100% homens

2. **Cluster 1**:
   - Perfil de Compra: Compra mais frequentemente
   - Gênero: ~40% mulheres e ~60% homens

## Como Usar

1. Clone este repositório
2. Instale as dependências necessárias
3. Abra o notebook `main.ipynb` em um ambiente Jupyter
4. Execute as células em ordem para reproduzir a análise
