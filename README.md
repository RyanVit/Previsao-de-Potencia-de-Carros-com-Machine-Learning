# Previsao-de-Potencia-de-Carros-com-Machine-Learning
Este projeto utiliza PySpark na plataforma Databricks para prever a potência de carros (HP) com base em características como Consumo, Cilindros e Cilindradas. Através de um modelo de regressão linear, o projeto realiza a análise, o treinamento e a avaliação do modelo usando o erro quadrático médio (RMSE).

Etapas do Projeto
Exploração dos Dados

Leitura do arquivo CSV contendo dados sobre os carros.
Inspeção inicial dos dados e exibição das primeiras linhas.
Pré-processamento dos Dados

Seleção das colunas relevantes: Consumo, Cilindros, Cilindradas, HP.
Vetorização das características de entrada usando VectorAssembler.
Divisão dos Dados

Divisão dos dados em dois conjuntos: Treinamento (70%) e Teste (30%).
Construção e Treinamento do Modelo

Criação de um modelo de regressão linear.
Treinamento do modelo com o conjunto de dados de treinamento.
Previsões

O modelo faz previsões sobre o conjunto de dados de teste.
Avaliação de Performance

Avaliação do modelo usando RMSE (Root Mean Squared Error).
Tecnologias Utilizadas
PySpark: Framework para processamento distribuído de dados e criação de modelos de Machine Learning.
Python: Linguagem de programação para implementação do código.
Databricks: Plataforma usada para rodar o código, processar dados e treinar o modelo.
Machine Learning: Utilização de regressão linear para previsão de uma variável contínua.
Como Rodar
Clone este repositório.

Importe o notebook para sua conta Databricks.

Certifique-se de ter o PySpark instalado em seu ambiente Databricks.

Execute as células na seguinte ordem:

Carregue e processe os dados.
Treine o modelo de regressão linear.
Avalie a performance do modelo.
Utilize o arquivo Carros.csv para realizar o treinamento e testar as previsões.

Estrutura do Repositório
carros.csv:
explorar.ipynb: Notebook Jupyter com o script de exploração de dados, incluindo a leitura e análise inicial dos dados.
MI.ipynb: Notebook Jupyter com o script de treinamento, onde o modelo de regressão linear é treinado e avaliado.
Resultados Esperados
O modelo será capaz de prever a potência (HP) dos carros com base nas suas características e será avaliado utilizando o RMSE. O desempenho do modelo pode ser melhorado com ajustes nos parâmetros ou no pré-processamento dos dados.

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

Licença
Este projeto está licenciado sob a MIT License.
