🏦 Previsão de Score de Crédito (AI Credit Scoring)
Este projeto simula um problema real de uma instituição financeira que deseja automatizar a classificação de crédito de seus clientes para agilizar processos e reduzir riscos.

🎯 Objetivo
Criar um modelo de Machine Learning capaz de ler o histórico financeiro de um cliente e prever automaticamente seu Score de Crédito: Good (Bom), Standard (Padrão) ou Poor (Ruim).

🛠️ Tecnologias Utilizadas
Python (Linguagem principal)

Pandas (Análise e manipulação de dados)

Scikit-Learn (Criação e treinamento dos modelos de Machine Learning)

📊 Resultados
Foram testados dois modelos: K-Nearest Neighbors (KNN) e Random Forest.

O modelo Random Forest obteve a melhor performance, com uma acurácia superior a 82%.

Identificou-se que as variáveis dias_atraso e divida_total são as mais determinantes para o score.

🚀 Como Executar
Clone o repositório.

Instale as dependências: pip install pandas scikit-learn seaborn.

Execute o notebook credit_score_prediction.ipynb.