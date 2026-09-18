# Aprendizado-de-M-quina---Cubo-Gelatinoso---2-Semestre-Ilum

# Cubo Gelatinoso - Classificação de Doença Renal Crônica (CKD)

Esta tarefa tem o intuito de trabalhar com os conceitos iniciais de Machine Learning, utilizando um dataset sobre Doença Renal Crônica (CKD) como base para criar e treinar modelos KNN (K Nearest Neighbors).

Como o *target* é binário (correspondendo a ter ou não ter CKD), foi utilizado o **K Nearest Neighbors Classifier**. O projeto passa pelas seguintes etapas:

* Ler o dataset e compreender seus dados e atributos;
* Definir o atributo target e dividir o target das features;
* Dividir os dados entre treino e teste;
* Imputar, encodar (One Hot Encoder) e normalizar os dados;
* Implementação de um modelo *baseline* para comparação de desempenho;
* Criação e treinamento de 12 modelos com hiperparâmetros diferentes, variando:
  * O valor de K;
  * A métrica de distância (euclidiana e manhattan);
  * O conjunto de atributos utilizados durante o treinamento (todos e subset). O subset foi definido a partir de estudos científicos sobre a correlação entre diferentes parâmetros e o CKD;
* Criação e treinamento de 3 modelos com métricas de distância diferentes (euclidiana, manhattan e chebyshev);
* Análise detalhada de todos os resultados por meio de gráficos;
* Conclusões e principais aprendizados;
* Interações com a AI e referências.
