# [Dataset-cars](https://github.com/icaroalmeidas/Python/blob/main/Analise%20car%20price%20prediction.ipynb)
This repository was made to explain the project of **[Sklearn](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)**:

## Objectives:
Verificar se existe alguma relação entre as variaveis. 

Existe alguma relação em quanto maior o numero de donos do carro menor o preço de venda?
Existe alguma relação entre a depreciação e o ano do carro? Forte ou fraca?

## DataSet

![image](https://github.com/icaroalmeidas/Python/assets/106759439/0bbd0e40-2ee9-4247-8469-bb8487de455f)
 
Podemos verificar a base de dados na imagem acima a falta de uma coluna com a depreciação dos carros.

Por este motivo abaixo calculamos a depreciação e adicionamos uma coluna a base de dados com a depreciação de cada carro e já vizualizamos a depreciação média.

![image](https://github.com/icaroalmeidas/Python/assets/106759439/94e5d9da-e1db-42ba-891c-a9bfa1e13c45)

## Mapa de calor

Aqui analisando o nosso mapa de calor podemos verificar as relações entre as variaveis.


![image](![Heatmap_image](https://github.com/icaroalmeidas/Python/assets/106759439/2338ecba-fe25-4a40-ad7e-32fcdf118628)

Analisando o mapa de calor podemos verificar que há uma forte relação entre a Depreciação e o ano do carro.
Preço de venda e o preço atual tem uma relação forte de 0.88. 
Depreciação e o ano do carro tem uma relação forte de 0.8.

Estes numeros confirmam o que acontece na realidade dos preços dos carros.

## Principais bibliotecas
- Pandas,Numpy ,Matplotlib e Seaborn.
- 
## You can find me at:
&nbsp;<a href="https://www.linkedin.com/in/brunofcb/">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white">
</a>&nbsp;

## Stages of Code Development:
- Importation and Familiarization with the Dataset.
- I noticed early on that class 0 could be easily separated, but classes 1 and 2 were closer together.
- After removing class 0 and comparing only classes 1 and 2, I used the decision tree method for separation.

## Results and Submission on Kaggle.
- I used various metric parameters to assess the accuracy of the method, including Recall, Accuracy, Precision, and the confusion matrix, ensuring minimal error in all cases. 
  
![image](https://github.com/BrunoFelipeCB/Dataset-iris/assets/99086238/26f37a46-bf5a-4e5b-aca8-276ebfee25ab)
