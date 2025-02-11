# Beta Bank Churn Prediction

Este projeto visa prever a saída de clientes do Beta Bank utilizando dados históricos sobre o comportamento dos clientes e rescisões de contratos. Manter clientes é mais rentável do que adquirir novos, por isso a capacidade de prever a perda de clientes é essencial para o banco.

# Objetivo
O objetivo é construir um modelo de machine learning capaz de prever se um cliente deixará o banco em breve. O principal critério de avaliação será o F1-score, que deverá ser no mínimo 0,59 no conjunto de dados de teste. Além disso, o desempenho será avaliado com a métrica AUC-ROC, comparando-a com o F1-score.

# Etapas do Projeto
1. Análise Exploratória de Dados (EDA): Entendimento dos dados, verificação de consistência e identificação de padrões relevantes.
2. Pré-processamento: Tratamento de valores ausentes, transformação de variáveis e normalização de dados.
3. Divisão dos Dados: Separação dos dados em conjuntos de treino e teste.
4. Construção de Modelos: Treinamento de diferentes algoritmos de classificação (ex.: Random Forest, Decision Tree, etc.).
5. Avaliação de Modelos: Comparação de desempenho com base no F1-score e na métrica AUC-ROC.
6. Ajuste de Hiperparâmetros: Busca pelos parâmetros ideais para maximizar o desempenho do modelo.
7. Conclusão: Seleção do melhor modelo e análise final dos resultados.

# Tecnologias Utilizadas
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn (para visualização de dados)
Jupyter Notebook

# Resultados Esperados
1. Um modelo preditivo com F1-score de pelo menos 0,59 no conjunto de teste.
2. Comparação detalhada entre o desempenho do modelo em termos de F1-score e AUC-ROC.