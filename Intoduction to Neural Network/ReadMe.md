# Introduction
In this Notebook we will be creating some scalar vector and try to build relation between features and labels and train the model by using neural networks(Tensorflow) .
To see whether our model is able to predict the relation between features and labels which we have created

In this Notebook there are series of steps which i have performed:
1. Modelling With TensorFlow
2. Improving a model
3. Evaluating a model
4. Visualizing the data and model Predictions.

### Steps in modelling with Tensorflow

1. **Creating a model** - define the input and output layers as well as the hidden layers of a deep learning model.
2. **Compiling a model** - define the **loss** function (in other words the function which tells our model how wrong it is) and the **optimizer** (tells our model how to improve the patterns its learning) and **evaluation metrices(what we can use to interpret the performance of our model).
3. **Fitting a model** - letting the model to try to find patterns between X & y (features and labels)

### Improving a model

1. **Creating a model**: By adding more layers , increase the number of hidden layers ( also called neurons) withing each of the hidden layers change each activation function

2. **Compiling a model** : change the optimization function or change the **learning rate** of the optimization function.

3. **Fitting a model**: here we might fit a model for more epochs( leave it training for longer period) or on more data (give the model more data to learn patterns)

### Evaluation our model prediction with regression evaluating metrices

Depending on the problem we are working on , there will be so many evaluation metrics


This problem is based upon the regression probelem So we are going to look for the regression evaluation metrics


There are two regression evaluation metrices

* 1. MAE - Mean Absolute Error
* 2. MSE - Mean Square Error
* 3. Huber - Combination of MAE and MSE

### Visualizing the data

WE all know visualizing the data helps us to understand the data pretty well.

![image](https://user-images.githubusercontent.com/91750738/177253741-7665aba7-82b1-481d-93ac-c21be28c29b7.png)

### Visualizing the model Predctions with the data

We have created a function from which we can plot the data into the scatter graph so that we can see the deviation from what model is predicting and what it has to actually predict
(Note : This values are scalar so that's why it was easy to show in the graphical format or else it will throw the error of the shapes.)

![image](https://user-images.githubusercontent.com/91750738/177253970-6554e730-fee9-4e9c-aca2-9417953f2949.png)

From the abpve image it is clearly visible that predictions is not that correct as compared to the testing data
so we try to improve our model through various way and we got the final one which perfetly overlaps the test data that means our model is predicting very correctly test data :)

![image](https://user-images.githubusercontent.com/91750738/177254142-189d59f1-0fb8-43db-85b8-5e8e5a0ffd53.png)


