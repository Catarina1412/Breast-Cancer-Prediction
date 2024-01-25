# Breast Cancer Prediction
 
 ## EN

_In this repository, you will find various files related to a completed project. Included are a detailed project report, the dataset used, and the Jupyter notebook implementing the project._

Files:
* [Breast Cancer Classification.ipynb](<Breast Cancer Classification.ipynb>): contains the Jupyter notebook with the project code
* [data.csv](data.csv): contains the data used in the project
* [Paper-Breast Cancer Classification.pdf](<Paper-Breast Cancer Classification.pdf>): project paper/report in English
* [Paper-Classificação de cancro da mama.pdf](<Paper-Classificação de cancro da mama.pdf>): project paper/report in Portuguese

**Objective:**

The aim of this project is to predict breast cancer from a dataset.

**Dataset Description:**

Breast cancer is the most diagnosed cancer in women, accounting for 1 in 4 annual cancer cases worldwide. In 2020, the incidence in the WHO Europe region was estimated at 576,300, and in the EU-27, it was 355,500. Approximately 21% of breast cancer cases in Europe occur in women under 50 years old, while 35% occur between 50 and 64 years old, and the remaining cases affect women above this age group. One in 11 women in the EU-27 will develop breast cancer before the age of 74.

In this project, I used the Wisconsin Breast Cancer Dataset (WBCD) from the UCI Machine Learning repository, which provides very solid and useful information for the sole purpose of building models to predict whether cancer is benign or malignant. The dataset I worked with has 32 attributes (the 'ID' attribute is omitted) and 568 instances. 


**Project Description:**

The project followed several stages, including:

_Data Exploration:_ Visualizing the data and dataset size, analyzing the types of data in the dataset, transforming the 'diagnosis' column into 0 or 1, representing the distribution of cancer (malignant/benign), studying the relationship between the data using a pairplot from the seaborn library. An analysis of data correlation was also performed using a correlation matrix and a heatmap from the seaborn library.

_Pre-processing:_ Removing the 'Id' variable, identifying and treating missing values.

_Models:_ The data was split into X_train, X_test, y_train, and y_test sets, keeping 45% of the data for testing. It was discovered the need to scale the data using StandardScaler from the sklearn library Subsequently, eight models were used: Neural Network, KNeighborsClassifier, GaussianNB, linear SVC, rbf SVC, Logistic Regression, Decision Tree, and Random Forest Classifier.

_Results:_ Among the evaluated models, rbf SVC achieved the best results, reaching an accuracy of 0.98.




## PT

_Neste repositório, encontrar-se-ão diversos ficheiros relacionados com um projeto concluído. Incluem-se um relatório detalhado do projeto, o conjunto de dados utilizado e o Jupyter notebook da implementação do projeto._

Ficheiros:
* [Breast Cancer Classification.ipynb](<Breast Cancer Classification.ipynb>): contém o jupyter notebook com o código do projeto
* [data.csv](data.csv): contém os dados usados no projeto
* [Paper-Breast Cancer Classification.pdf](<Paper-Breast Cancer Classification.pdf>): paper/relatório do projeto em inglês
* [Paper-Classificação de cancro da mama.pdf](<Paper-Classificação de cancro da mama.pdf>): paper/relatório do projeto em português

**Objetivo:**

O objetivo deste projeto é detetar o cancro da mama a partir de um conjunto de dados.

**Descrição do Dataset:**

O cancro da mama é o cancro mais diagnosticado em mulheres, representando 1 em cada 4 casos anuais de cancro em todo o mundo. Em 2020, a incidência na região da OMS na Europa foi estimada em 576.300, e na UE-27 foi de 355.500. Aproximadamente 21% dos casos de cancro da mama na Europa ocorrem em mulheres com menos de 50 anos, enquanto 35% ocorrem entre os 50 e os 64 anos, e os restantes casos afetam mulheres acima dessa faixa etária. Uma em cada 11 mulheres na UE-27 desenvolverá cancro da mama antes dos 74 anos.

Neste projeto, utilizei o Conjunto de Dados Público de Cancro da Mama de Wisconsin (WBCD) do repositório de Machine Learning da UCI, que fornece informações muito sólidas e úteis com o único propósito de construir modelos para prever se o cancro é benigno ou maligno. O conjunto de dados com o qual trabalhei possui 32 atributos (o atributo 'ID' é omitido) e 568 instâncias. 


**Descrição do Projeto:**

O projeto seguiu várias etapas, incluindo:

_Exploração de dados:_ Visualização dos dados e do tamanho do conjunto de dados , análise do tipo de dados existentes no conjunto de dados e transformação da coluna “diagnosis” em 0 ou 1, representação da distribuição do cancro(maligno/benigno), estudo da relação entre os dados através de um pairplot da biblioteca seaborn .Também foi realizada uma análise da correlação dos dados usando uma matriz de correlação e um heatmap da biblioteca seaborn.

_Pré-processamento:_ Eliminação da variável “Id”, identificação e eliminação de valores em falta.

_Modelos:_ : Os dados foram divididos em conjuntos X_train, X_test, y_train e y_test, reservando 45% dos dados para teste. Verificou-se a necessidade de escalar os dados usando o StandardScaler da biblioteca sklearn. Posteriormente, foram utilizados oito modelos: Neural Network, KNeighborsClassifier, GaussianNB, SVC linear,  SVC rbf, Logistic Regression, Decision Tree e Random Forest Classifier.

_Resultados:_ Entre os modelos avaliados, o SVC rbf obteve os melhores resultados, alcançando uma accuracy de 0.98.
