# 🏦 Previsão de Score de Crédito (AI Credit Scoring)

Este projeto simula um problema real de uma instituição financeira que deseja automatizar a classificação de crédito de seus clientes para agilizar processos e reduzir riscos.

## 🎯 Objetivo de Negócio
Criar um modelo de Machine Learning capaz de ler o histórico financeiro de um cliente e prever automaticamente seu Score de Crédito: **Good** (Bom), **Standard** (Padrão) ou **Poor** (Ruim).

## 🛠️ Tecnologias Utilizadas
* **Python** (Linguagem principal)
* **Pandas** (Análise e manipulação de dados)
* **Scikit-Learn** (Criação e treinamento dos modelos de Machine Learning)
* **Matplotlib/Seaborn** (Visualização de dados e métricas)

## 📊 Resultados Alcançados
Foram testados dois modelos de classificação: **K-Nearest Neighbors (KNN)** e **Random Forest**.

* 🏆 **Melhor Modelo:** O **Random Forest** obteve a melhor performance, com uma acurácia superior a **82%**.
* 🔍 **Insights:** A análise das features mostrou que as variáveis **"Dias de Atraso"** e **"Dívida Total"** são os fatores mais determinantes para o score de crédito, superando dados demográficos como profissão.

## 🚀 Como Executar o Projeto
1. Clone este repositório.
2. Instale as dependências necessárias:
   ```bash
   pip install pandas scikit-learn seaborn matplotlib
