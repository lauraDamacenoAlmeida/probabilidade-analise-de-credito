# Calcular a probabilidade de um solicitante ir para a análise de crédito

Esse notebook tem como objetivo construir um modelo de classificação que retorne a probabilidade que um cliente tem de ser enviado para análise de crédito dado que ele foi pré-aprovado para o empréstimo com garantia de automóvel.

## Requisitos

1. [Pandas](https://pandas.pydata.org/docs/): para leitura e manipulação de dados

2. [https://matplotlib.org/](https://matplotlib.org/): para criar o gráfico de barras

3. [Seaborn](https://seaborn.pydata.org/): para criar o gráfico de barras

4. [Pycaret](https://pycaret.gitbook.io/docs/): para realizar o AutoML

5. [sklearn](https://scikit-learn.org/stable/install.html): para criação de modelos de machine learning

6. [numpy](https://numpy.org/): para realizar calculos e operações de manipulação de estrutura de dados

7. [scipy](https://scipy.org/install/): para realizar testes estatísticos

8. [imblearn](https://imbalanced-learn.org/stable/): para realizar o método de balanceamento de classes

9. [Alibi](https://docs.seldon.io/projects/alibi/en/stable/overview/high_level.html): para realizar o método de explicabilidade dos modelos

10. [imblearn](https://imbalanced-learn.org/stable/): para realizar o método de balanceamento de classes

11. [Pandas Profilling](https://pypi.org/project/pandas-profiling/): para realizar o método de análise de dados automática

## Estrutura do projeto
- Untitled.ipynb: notebook com os códigos das análises, insights extraídos e construção do modelo.
- dataset.csv: arquivo com os dados
- description.csv : arquivo com a descrição dos campos dos dados
- environment.yml: arquivo yml para instalar as bibliotecas
- modelo_auto.pkl: arquivo com o modelo pkl


## Como usar:
1. Baixar o projeto
2. Dentro do terminal do anaconda rodar: 
```
conda env create -f environment.yml --name env_auto
```
3. Ativar o ambiente virtual
```
conda activate env_auto
```
4. Após a ativação é necessário rodar o seguinte comando:
```
jupyter notebook
```
5. Acessar a pasta do projeto e abrir o arquivo .ipynb

6. Rodar os códigos na ordem mostrada no tópico "Etapas de execução do notebook"
