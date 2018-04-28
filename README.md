# Prevendo salários de vagas de emprego

## Instruções para execução do código

### Pré-requisitos

O desenvolvimento deste projeto foi realizado em Python 2.7 em um Jupyter Notebook.

As seguintes bibliotecas são necessárias para a execução do projeto:

- pandas
- numpy
- scipy
- sklearn
- matplotlib
- gensim

### 1º passo: Baixar conjunto de dados

O conjunto de dados utilizado neste projeto pode ser obtido na plataforma Kaggle, no seguinte endereço:

https://www.kaggle.com/PromptCloudHQ/us-jobs-on-monstercom

É necessário descompactar o arquivo `.zip` e colocar o arquivo `monster_com-job_sample.csv` no mesmo diretório do Jupyter Notebook `prevendo_salarios.ipynb`.

### 2º passo: Baixar o modelo Word2Vec pré-treinado

Neste projeto foi utilizado o modelo Word2Vec pré-treinado do Google, que pode ser obtido no seguinte endereço:

https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing

(**Atenção**: é um arquivo bem grande, ao ser descompactado ele ocupa em torno de 3,6 GB)

É necessário descompactar o arquivo `.bin.gz` e colocar o arquivo `GoogleNews-vectors-negative300.bin` no mesmo diretório do Jupyter Notebook `prevendo_salarios.ipynb`.

### 3º passo: Execução

Uma vez que os dois arquivos acima foram baixados e descompactados no diretório correto, basta iniciar o Jupyter Notebook `prevendo_salarios.ipynb` e executar o código.
