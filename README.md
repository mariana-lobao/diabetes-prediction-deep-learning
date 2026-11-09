# diabetes-prediction-deep-learning
Projeto de Deep Learning para classificação de casos de diabetes utilizando redes neurais artificiais (MLP)

## Sobre o projeto:
Este projeto tem como objetivo colocar em prática os conhecimentos adquiridos na minha pós-graduação em Ciência de Dados Aplicada à Saúde, por meio do uso de Deep Learning e redes neurais. Mais especificamente, foi utilizada uma rede neural feedforward (ou MLP — Multilayer Perceptron).

## Etapas do projeto:
- Verificação de dados nulos.
- Remoção de dados duplicados.
- Análise exploratória dos dados (EDA).
- Pré-processamento das variáveis categóricas e numéricas.
- Divisão dos dados em treinamento, validação e teste.
- Treinamento de três modelos MLP com a mesma arquitetura, utilizando diferentes configurações de treinamento.
- Comparação dos resultados nos dados de validação.
- Seleção do modelo e avaliação final nos dados de teste.

## Tecnologias utilizadas:
- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

## Resultados:
Nos dados de teste, o terceiro modelo apresentou accuracy de 0,91, precision de 0,48, recall de 0,89 e F1-score de 0,62 para a classe com diabetes. Os resultados foram semelhantes aos obtidos na validação, indicando um desempenho relativamente consistente em dados não utilizados durante o treinamento.

## Limitações:
Apesar do bom recall, a precision relativamente baixa indica uma quantidade considerável de falsos positivos, ou seja, pessoas sem diabetes classificadas incorretamente como positivas.

## Possíveis melhorias:
Investigar diferentes thresholds de classificação, testar técnicas de balanceamento das classes e comparar o desempenho com outros algoritmos. 

## Fonte dos dados:
O dataset utilizado está disponível no Kaggle:
https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset

O arquivo CSV não está incluído neste repositório. Para executar o notebook, é necessário baixar o dataset na fonte original e colocá-lo na pasta do projeto com o nome diabetes_prediction_dataset.csv.
