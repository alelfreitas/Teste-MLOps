# Desafio para admissão na  J&F Tech para o cargo de MLOps

**Objetivos**: Aplicar os modelos de classificação Naive Bayes Gaussiano e Árvores de Decisão (usando os critérios Gini e Entropia) em uma base de dados. Comparar os resultados usando as métricas de acurácia, precision, recall, f1-score e a matriz de confusão de cada modelo. Utilizar técnicas de balanceamento de classes e seleção de features para melhorar os resultados.

**Desafios:**

1. Base de Dados: Utilize a base de dados renda.csv, disponível nesse repositório, que contém informações para analisar a renda de indivíduos com base em diferentes variáveis demográficas e de emprego.. A base de dados possui 32.560 entradas e 15 colunas. Abaixo está um resumo das colunas e seus respectivos tipos de dados:
   - Idade
   - Tipo de empregador
   - Número de identificação
   - Nível educacional
   - Anos de educação
   - Estado civil
   - Ocupação
   - Relação familiar
   - Raça
   - Sexo
   - Ganho de capital
   - Perda de capital
   - Horas trabalhadas por semana
   - País de origem
   - Faixa salarial (<=50K ou >50K)
2. Preparação dos Dados:
   - Divida os dados em conjuntos de treinamento e teste (75% para treinamento e 25% para teste).
   - Realize a transformação e normalização dos dados, se julgar necessário.
3. Balanceamento das Classes:
   - Utilize técnicas de balanceamento de classes, como oversampling ou undersampling, para lidar com possíveis desequilíbrios na distribuição das classes.
4. Seleção de Features:
   - Realize a seleção de features utilizando técnicas como Análise de Componentes Principais (PCA) ou seleção baseada em importância de features para melhorar o desempenho dos modelos.
5. Modelagem:
   - Aplique o modelo de Naive Bayes Gaussiano nos dados de treinamento.
   - Aplique o modelo de Árvore de Decisão usando o critério Gini nos dados de treinamento.
   - Aplique o modelo de Árvore de Decisão usando o critério Entropia nos dados de treinamento.
6. Avaliação dos Modelos:
   - Utilize o conjunto de teste para fazer previsões com cada modelo.
   - Calcule as seguintes métricas para cada modelo: acurácia, precision, recall, f1-score.
   - Gere a matriz de confusão para cada modelo.
7. Análise dos Resultados:
   - Compare os resultados das métricas para os três modelos.
   - Discuta as diferenças observadas nas métricas e na matriz de confusão entre os modelos.
   - Analise quais características dos modelos e das técnicas de balanceamento e seleção de features podem ter contribuído para as diferenças de desempenho.
8. Nova Aplicação dos Modelos:
    - A partir da análise dos resultados verifique a necessidade de fazer mudanças na base ou nos modelos para melhorar o desempenho.
    - Aplique novamente os modelos, avalie os modelos e analise os resultados.
9. Salvamento:
    - Salve o modelo treinado em um formato adequado (como pickle para Python, ou um formato específico da biblioteca usada, como .h5 para Keras ou .joblib para scikit-learn).
