[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChandrashekharRobbi/Convolutional-Neural-Network-or-Neural-Network-with-Tensorflow/blob/main/Regression%20Neural%20Networks/Regression%20Problems/Medical%20Insurance/medical_insurance.ipynb)
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


![image](https://user-images.githubusercontent.com/91750738/178978479-19fffffe-2405-49ae-a473-5e856b8ba51f.png)


# 2. Create the baseline model

Baseline model started with the 2 Dense layers ( we have to always start with the lowest layers and increase gradually in improve stage)

![image](https://user-images.githubusercontent.com/91750738/178977877-360284d8-a923-4edd-a2f7-377e4293ba74.png)


# 3. Evaluate the model


In this stage we will be able to see how much model has learned the patterns and how perfect our model can predict the insurance price


i have use the evaluation metrices as (MAE) 


![image](https://user-images.githubusercontent.com/91750738/178978519-096657ec-69a5-4279-a122-953a76409335.png)


# 4. Improve the model


we have to imporve the model by :
1. adding more layers
2. changing the activation function
3. changing the learning rate
