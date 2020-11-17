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

##### Dependências
- python3
- pyspark 3.0.1 
- mlflow
- jupyter

##### Rodando o Projeto 2
- Primeiramente o rode o jupyter notebook na pasta que se encontra o notebook do projeto 2.
```
$ jupyter notebook
```
- Após abrir o jupyter no seu navegador, crie um novo terminar no próprio app do jupyter e rode o comando para iniciar o mlflow
```
$ mlflow ui
```
Com o mlflow rodando, agora já é possível rodar o notebook do projeto 2.
**Obs: é importante rodar o mlflow no terminal do jupyter pois em nossos testes não funcionou rodando no terminal local.**

Grupo:
- Douglas Soares (dsl)
- Jônatas Clementino (joc)

Professor:
- Luciano Andrade
