# Projeto Final da EBAC
Objetivo é desenvolver um modelo de "credit scoring" através de regressão logística e criar um Pipeline pra executar o modelo
# Descrição do Projeto
Neste projeto, construimos um credit scoring para cartão de crédito, em um desenho amostral com 15 safras, utilizando 12 meses de performance. Carregamos a base de dados e foi feito uma amostragem separando os três últimos meses como safras de validação out of time (oot). Avaliamos os dados através descritivas básicas univariada e bivariada pra desenvolver um modelo de regressão logística. Depois para criar um pipeline utilizando o sklearn pipeline, houve pré-processamento substituindo valores nulos. Colocamos no pipeline para reduzir a dimensionalidade (PCA), um "Scaler" para padronizar os dados e um modelo de regressão logística. Depois houve a divisão dos dados em treino e teste, criação de dummies e aplicação do pipeline. Também foi feito análise de qual modelo aplicaria melhor aos dados utilizando "Pycaret", aplicamos o melhor modelo e depois executamos o modelo "lightgbm".

# Aplicação Rodando no Streamlit

https://github.com/user-attachments/assets/c5c25d8e-5f8d-4ff4-9511-c9291cfffea0

# Nomes dos desenvolvedores do projeto e informação para entrar em contato.

Heber Rossi
@heberrossi
