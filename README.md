# 🏦 Previsão de Score de Crédito com IA

Este projeto aplica técnicas de **Machine Learning** para resolver um problema clássico de instituições financeiras: a análise automática de risco de crédito.

O objetivo é classificar novos clientes em três categorias de risco (**Good**, **Standard** ou **Poor**) com base em seu histórico financeiro, automatizando um processo que antes era manual.

## 📊 O Desafio
Um banco possui uma base de dados histórica de clientes e deseja criar um modelo preditivo capaz de:
1.  Ler as informações financeiras de um novo cliente.
2.  Classificar automaticamente seu *Score de Crédito*.
3.  Atingir uma acurácia superior a 80% nas previsões.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas:** Manipulação e análise de dados tabulares.
* **Scikit-Learn:** Criação e treinamento dos modelos de Machine Learning.
    * *LabelEncoder:* Para tratamento de variáveis categóricas (texto em números).
    * *RandomForestClassifier:* Algoritmo de Árvores de Decisão.
    * *KNeighborsClassifier:* Algoritmo KNN (Vizinhos Próximos).

## ⚙️ Funcionalidades do Notebook
1.  **Análise Exploratória:** Importação e visualização inicial da base `clientes.csv`.
2.  **Tratamento de Dados:**
    * Conversão de colunas de texto (`profissao`, `mix_credito`, etc.) em valores numéricos essenciais para a IA usando `LabelEncoder`.
3.  **Machine Learning:**
    * Divisão da base em dados de **Treino (70%)** e **Teste (30%)**.
    * Treinamento comparativo entre dois modelos: **Árvore de Decisão** vs **KNN**.
4.  **Avaliação de Performance:** Cálculo da acurácia de cada modelo com dados nunca vistos antes.

## 📈 Resultados
Após os testes, o modelo **Random Forest (Árvore de Decisão)** apresentou o melhor desempenho:

* **Acurácia Random Forest:** ~82% ✅ (Modelo Escolhido)
* **Acurácia KNN:** ~74%

O modelo vencedor foi utilizado para processar a base `novos_clientes.csv` e gerar as previsões finais de risco.

## 📦 Como executar
1.  Clone o repositório.
2.  Instale as dependências:
    ```bash
    pip install pandas scikit-learn ipykernel
    ```
3.  Abra o arquivo `.ipynb` no VS Code ou Jupyter Notebook.
4.  Execute as células sequencialmente ("Run All").

---
*Projeto desenvolvido durante a Jornada Python da Hashtag Treinamentos.*
