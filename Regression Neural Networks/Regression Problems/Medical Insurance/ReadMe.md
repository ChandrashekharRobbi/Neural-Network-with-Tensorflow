# Medical Insurance 


In this project i have used the medical insurance dataset from the kaggle website to predict the charges of the medical insurance by using few parameters

It was a number right??

Then this problem is a **Regression Problem**


Like wise i did this project in several steps


The steps include:
# 1. Understand & preprocessed the data

It is very necessary to understand the data because it makes clear about the parameters / features present in the dataset and it is also necessary to visualize them to understand much better


Then i have also preprocessed the data by using `pd.get_dummies()` (one hot encoder)

![image](https://user-images.githubusercontent.com/91750738/178977384-2d758c36-8c3d-4d24-9e44-6a6a5f00bfc1.png)


2. Create the baseline model

Baseline model started with the 2 Dense layers ( we have to always start with the lowest layers and increase gradually in imporve stage)

![image](https://user-images.githubusercontent.com/91750738/178977877-360284d8-a923-4edd-a2f7-377e4293ba74.png)


3. Evaluate the model


In this stage we will be able to see how much model has learned the patterns and how perfect our model can predict the insurance price


i have use the evaluation metrices as (MAE) 
. Improve the model
