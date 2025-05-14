## 🎯 Objetivo

Construir um modelo preditivo capaz de classificar clientes com base em dados tabulares utilizando Random Forest Classifier, visando auxiliar em decisões de negócio, segmentação e análise comportamental.

---

## 🔍 Principais Etapas

- **Carregamento dos dados:** leitura do CSV com os dados de clientes;
- **Análise exploratória:** visualizações com Seaborn e Matplotlib;
- **Pré-processamento:** normalização com `StandardScaler`;
- **Divisão dos dados:** separação em treino e teste com `train_test_split`;
- **Modelagem:** utilização de `RandomForestClassifier`;
- **Avaliação:** métricas de acurácia e F1-score, além de matriz de confusão.

---

## 🛠️ Tecnologias e Bibliotecas

- Python 3.10+
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- FastAPI (planejado)

---

## 📊 Resultados Obtidos

O modelo Random Forest apresentou desempenho satisfatório na base de teste, sendo avaliado por métricas como:

- Acurácia
- F1-Score (ponderado)
- Matriz de confusão

---

## 🚀 Como Executar Localmente

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/ml-classificacao-clientes.git
cd ml-classificacao-clientes


# 🧠 Projeto de Classificação com Machine Learning

Este projeto realiza uma análise de dados e aplica algoritmos de machine learning para classificar dados a partir de um dataset fornecido. Ele foi inicialmente desenvolvido em um notebook Colab e depois estruturado para ser facilmente transformado em uma aplicação Python e uma API com FastAPI.

## 📁 Estrutura do Projeto

├── data/
│ └── bootcamp_train.csv # Dataset utilizado na análise
├── notebooks/
│ └── Trabalho_1_melhorado.ipynb # Notebook reestruturado com explicações e visualizações
├── src/
│ ├── processing/ # Pré-processamento de dados
│ ├── models/ # Treinamento e avaliação de modelos
│ ├── utils/ # Métricas e visualizações
│ └── main.py # Ponto de entrada do sistema/API
├── README.md
└── requirements.txt # Dependências do projeto


## 🚀 Objetivos

- Realizar a exploração inicial dos dados;
- Tratar dados ausentes e normalizar variáveis;
- Treinar modelos de classificação com `scikit-learn`;
- Avaliar o desempenho com métricas como acurácia e F1-score;
- Exibir os resultados com visualizações gráficas;
- Preparar o código para publicação como uma API REST.

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib / Seaborn / Plotly / Altair
- FastAPI (para publicação futura como API)

## 📊 Resultados Esperados

- Um modelo de classificação treinado e validado;
- Relatórios de desempenho e matriz de confusão;
- Código modularizado e reutilizável;
- Possibilidade de integração com sistemas web via API.

## 📦 Como Usar

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/projeto-classificacao-ml.git
cd projeto-classificacao-ml
