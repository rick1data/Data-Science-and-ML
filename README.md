# Projeto de Análise de Dados e Machine Learning
	
## Introdução
	
Este projeto foi desenvolvido como parte de um curso universitário, focando na análise de dados e na aplicação de algoritmos de Machine Learning. Utilizamos um dataset que contém informações sobre salários que podem ser <=50k ou >50k dólares anuais, dados de diversas pessoas, com o objetivo de explorar e prever os salários com base em diferentes características.
	
## Análise Exploratória de Dados
	
A primeira etapa do projeto envolve uma análise exploratória básica do dataset, utilizando a biblioteca **Pandas**. Durante essa fase, realizamos:
	
- **Limpeza e preparação dos dados:** Identificação e tratamento de valores ausentes e inconsistências.
- **Visualizações gráficas:** Utilizamos as bibliotecas **Matplotlib**, **Seaborn** e **Plotly** para criar gráficos que ajudam a entender as distribuições e correlações entre variáveis.
	
## Pré-processamento de Dados para Machine Learning
	
Antes de aplicar os algoritmos de Machine Learning, foi necessário realizar o pré-processamento dos dados:
	
- **Tratamento de atributos categóricos:** Utilizamos o **Label Encoder** e o **One-Hot Encoder** para converter variáveis categóricas em numéricas, uma vez que a maioria dos algoritmos de Machine Learning requer dados numéricos.
- **Normalização dos dados numéricos:** Aplicamos o **StandardScaler** para garantir que os dados numéricos estejam na mesma escala, evitando que certos atributos tenham mais influência do que outros.
	
## Algoritmos de Classificação
	
Utilizamos a biblioteca **Scikit-Learn** para implementar e testar diferentes algoritmos de classificação. Os modelos utilizados incluem:
	
- **Árvores de Decisão:** Acurácia de 82%
- **Random Forest:** Acurácia de 86%
- **K-Nearest Neighbors (KNN):** Acurácia de 83%
- **Logistic Regression (Regressão Logística): Acurácia de 85%**
- **Support Vector Machine (SVM):** Acurácia de 85%
- **Neural Networks (Redes Neurais):** Acurácia de 82%
	
	## Conclusão
	
	O projeto demonstrou a importância da análise exploratória e do pré-processamento adequado dos dados para o sucesso de modelos de Machine Learning. Os resultados obtidos mostram a eficácia de diferentes algoritmos, destacando o Random Forest e o SVM como os modelos mais precisos neste contexto.
	
	Para mais informações e detalhes sobre a implementação, consulte o NoteBook com o código-fonte disponível neste repositório.
