# model-prediction-churn_ds

Modelo para previnir o churn dos clientes, foi necessário dividir em seis passos:
 1- Preparando os dados: carregar os dados com SparkSQL e tratar os dados categóricos utilizando os dummies;
 2- Criando o primeiro modelo: regressão logística transformando os dados em VectorAssembler e medir o desempenho do modelo;
 3- Avaliando o novo modelo: avaliar a árvore de decisão, criar e treinar o modelo e medir o desempenho do modelo utilizando o MulticlassClassificationEvaluator;
 4- Comparação entre modelos: explicar o funcionamento do Random Forest Classifier, criar e treinar o modelo utilizando a biblioteca de MLlib do PySpark e medir o desempenho do modelo utilizando o MulticlassClassificationEvaluator;
 5- Técnicas de otimização: otimizar os hiperparâmetros utilizando ParamGridBuilder, testar os modelos utilizando o CrossValidator, comparar o desempenho dos modelos utilizando o MulticlassClassificationEvaluator;
 6- Criar o modelo final e testar com um novo cliente.
