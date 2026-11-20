# Classificação de Diabetes com KNN

## Objetivo

Este projeto tem como objetivo aplicar conceitos iniciais de Machine Learning por meio do algoritmo K-Nearest Neighbors (KNN), utilizando dados de glicose e IMC para classificar possíveis diagnósticos de diabetes.

## Tecnologias utilizadas

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Desenvolvimento

Inicialmente, os dados foram carregados utilizando a biblioteca Pandas. Em seguida, foram selecionadas duas características para a classificação:

- **Glicose:** nível de glicose no sangue.
- **IMC:** Índice de Massa Corporal.

A base de dados foi dividida em conjuntos de treinamento (70%) e teste (30%). Para a classificação, foi utilizado o algoritmo KNN com `k = 5`, ou seja, o modelo considera os cinco vizinhos mais próximos para determinar a classe de uma nova observação.

Por fim, as previsões foram comparadas com os resultados reais para avaliar o desempenho do modelo.

## Resultado

O modelo alcançou uma acurácia de **73,33%** nos dados de teste.

## Aprendizados

Durante o desenvolvimento, foram explorados conceitos fundamentais de Machine Learning, como:

- Separação entre variáveis de entrada e variável alvo.
- Divisão de dados em treinamento e teste.
- Treinamento de modelos com o método `fit()`.
- Realização de previsões com o método `predict()`.
- Avaliação de desempenho utilizando a acurácia.

## Observação

Este projeto possui finalidade exclusivamente educacional. O modelo não deve ser utilizado para diagnósticos médicos ou decisões relacionadas à saúde.
