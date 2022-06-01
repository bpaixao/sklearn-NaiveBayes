# sklearn-NaiveBayes
Classificação com sklearn - Modelo supervisionado Naive Bayes (NB)


A principal característica do algoritmo, e também o motivo de receber “naive” (ingênuo) no nome, é que ele desconsidera completamente a correlação entre as variáveis (features). Ou seja, se determinada fruta é considerada uma “Maçã” se ela for “Vermelha”, “Redonda” e possui “aproximadamente 10cm de diâmetro”, o algoritmo não vai levar em consideração a correlação entre esses fatores, tratando cada um de forma independente.

O algoritmo de Naive Bayes consiste em encontrar uma probabilidade a posteriori (possuir a doença, dado que recebeu um resultado positivo), multiplicando a probabilidade a priori (possuir a doença) pela probabilidade de “receber um resultado positivo, dado que tem a doença”.

Devemos também computar a probabilidade a posteriori da negação (Não possuir a doença, dado que recebeu um resultado Positivo).



Obs. Esse script foi criado utilizando o Notebook GoogleColab. 
