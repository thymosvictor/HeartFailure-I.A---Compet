# 🔥 Projeto de IA - Previsão de Falência Cardíaca

Este projeto tem como objetivo desenvolver um modelo de **Machine Learning** capaz de prever o risco de **falência cardíaca** em pacientes, com base em variáveis clínicas. O projeto faz parte do **Desafio COMPET - Inteligência Artificial na Prática**.

## 📂 Dataset

- **Projeto** Heart Failure Prediction Dataset
- **Fonte:** [Kaggle - Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
Contém registros de pacientes com atributos clínicos como idade, sexo, colesterol, tipo de dor no peito, frequência cardíaca máxima, entre outros.

## Objetivo

Construir um modelo de **classificação binária** que responda à pergunta:
"Este paciente apresenta risco de falência cardíaca? (1 = Sim, 0 = Não)"

## Etapas do Projeto

## Nível I

**Análise exploratória dos dados** (gráficos e correlação)
**Pré-processamento** (tratamento de variáveis categóricas e numéricas)
**Treinamento de dois modelos de machine learning:**
  - Random Forest Classifier
  - K-Nearest Neighbors (KNN)
**Avaliação dos modelos usando a acurácia**

## Nível II
**30 execuções de treino/teste para avaliar estabilidade dos modelos**
**Cálculo de média e desvio padrão da acurácia**
**Salvamento do melhor modelo usando `pickle`**
**Criação de uma interface gráfica interativa com `gradio`**
