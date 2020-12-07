## Trabalho para disciplina de **Deep Learning** do curso de **Especialização em Big Data, Data Science e Data Analytics** da Universidade do Vale do Rio dos Sinos - Unisinos - 2020/2
### **Autores:**
*   Diogo Gnutzmann Santos
*   Emanuel Luz de Abreu
*   Lissandra Dutra da Silva
*   Rodrigo Michel
*   Vinícius Silva Salinas

### **Objetivo**
O objetivo desse trabalho é gerar nota IMDB de um filme baseado em features, utlizando a aprendizagem profunda de máquina.

### **Problema** 
O problema definido consiste na necessidade de analisar os principais atributos dos filmes mais bem avaliados segundo suas respectivas notas IMDB e calcular notas de filmes atuais ou futuros que ainda não possuem esta avaliação. A partir do problema evidenciado, a solução consiste em criar análises prévias sobre a base de dados e gerar a nota IMDB de um filme baseado nos atributos detalhados abaixo conforme o dataset escolhido.
### **Dataset e Modelagem**

O dataset escolhido é uma coleção de filmes encontrados nas seguintes plataformas de streaming: Netflix, Prime Video, Hulu e Disney+. O arquivo do dataset usado para o estudo está hospedado na plataforma Kaggle, no seguinte endereço:
https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney

As features são:
* ID;
* Title: título do filme;
* Year: ano que o filme foi lançado;
* Age: faixa etária;
* IMDb: base de dados online de informação sobre música, cinema, filmes, programas e comerciais para televisão e jogos de computador (*);
* Rotten Tomatoes: website americano, agregador de críticas de cinema e televisão (***);
* Netflix:	plataforma de streaming (**);
* Hulu: plataforma de streaming (**);
* Prime Video: plataforma de streaming (**);
* Disney+: plataforma de streaming (**);
* Type: classifica a obra em filme ou série, contudo, neste dataset há apenas filmes (***);
* Directors:	diretor do filme;
* Genres: gênero do filme;
* Country: país de origem do filme;
* Language: idioma de origem do filme;
* Runtime: duração do filme.

(*) Esta feature possui a nota dada pelo IMDb.

(*) Esta feature assume o valor 1 se o filme está disponível na plataforma de streamming e 0 em caso contrário.

(***) Esta feature será excluída da amostra de dados e não entrará nos estudos dessa tarefa.


## **Refêrencias consultadas para criação do modelo**

* TensorFlow Basics: Tensor, Shape, Type, Graph, Sessions & Operators 
    https://www.guru99.com/tensor-tensorflow.html#1

* Keras: Regression-based neural networks
    https://datascienceplus.com/keras-regression-based-neural-networks/


* Regression Tutorial with the Keras Deep Learning Library in Python
    https://machinelearningmastery.com/regression-tutorial-keras-deep-learning-library-python/


* Incompatible input problem
    https://stackoverflow.com/questions/63307619/valueerror-input-0-of-layer-dense-1-is-incompatible-with-the-layer