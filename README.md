# Notebook-predict-price

README para o Projeto de Regressão Polinomial com Pipeline
Visão Geral do Projeto
Este projeto utiliza técnicas de regressão polinomial para prever o valor de notebooks com base em várias características, como marca, ano, quantidade de núcleos, memória RAM, entre outras. A análise é realizada utilizando pipelines para garantir um fluxo de trabalho eficiente e reprodutível.

Estrutura do Projeto
aula01.ipynb: Notebook contendo o código principal do projeto.
notebooks_nulos.csv: Dataset contendo as informações dos notebooks, incluindo valores nulos que precisam ser tratados.
Requisitos
Para executar este projeto, você precisará dos seguintes pacotes Python:

pandas
numpy
scikit-learn
matplotlib
seaborn
Você pode instalar todos os pacotes necessários usando o comando:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib seaborn
Passos para Executar o Projeto
Carregar o Dataset:
Carregar o dataset notebooks_nulos.csv e realizar uma inspeção inicial para entender a estrutura dos dados e identificar valores nulos.

Pré-processamento dos Dados:

Imputação de valores nulos nas colunas.
Normalização dos dados usando StandardScaler.
Transformação polinomial das características utilizando PolynomialFeatures.
Criação da Pipeline:
Criar uma pipeline que inclui as etapas de normalização, transformação polinomial e ajuste do modelo de regressão linear.

Treinamento e Avaliação do Modelo:

Dividir os dados em conjuntos de treinamento e teste.
Ajustar o modelo utilizando a pipeline.
Fazer previsões e calcular métricas de desempenho, como o erro médio quadrático (MSE) e a acurácia do modelo.
Validação Cruzada:
Aplicar validação cruzada para garantir a robustez do modelo.
