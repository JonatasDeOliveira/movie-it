### Movie It

#### Projeto 1
Analise sobre o [dataset de filmes](https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney) aplicando técnicas de:
- Preprocessamento 
- Análises estatísticas descritiva e visualizações
- Testes de hipóteses estatisticos

#### Projeto 2
Utilizamos o data set utilizado e processado no projeto 1 para predizer notas de filmes do IMDb
- Para seleção de features utilizamos todas que possuia um mutual information != 0
- Os seguintes algortimos foram utilizados:
  - Linear Regression
  - Decision Tree
  - MLP
  - Random Forest
- Fazemos uso do `MLflow` para guardar os experimentos, contendo todos os dados e resultados de cada iteração rodado
- Para seleção de hiper parâmetros utilizamos a ferramenta `Optuna`
- A partir do algotimo com maior R2 score e seus hiper parâmetros, tentamos melhorá-lo reduzindo a quantidade de dados e features

Obs.: Para rodar o projeto 2 utilizamos o jupyter notebook e também iniciamos o mlflow pelo terminal do mesmo.

Grupo:
- Douglas Soares (dsl)
- Jônatas Clementino (joc)

Professor:
- Luciano Andrade
