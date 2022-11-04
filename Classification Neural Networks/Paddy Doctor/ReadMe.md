[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChandrashekharRobbi/Convolutional-Neural-Network-or-Neural-Network-with-Tensorflow/blob/main/Classification%20Neural%20Networks/Paddy%20Doctor/PADDY%20DOCTOR.ipynb#scrollTo=SjTS31Un4o-j)
# PADDY DOCTOR

<hr>
Note: If you are using the notebook not in google colab then you have to download the datasets

Download the datasets from kaggle website:

> https://www.kaggle.com/competitions/paddy-disease-classification/data


Google Colab users can directly open notebook code itself takes care of downloading the dataset (you only have to provide kaggle API key if it is asked)

<hr>
The main objective of this project is to develop a deep learning-based model to classify the given paddy leaf images accurately.

This project is based on **Multiclass Classification**

**In this project i have achieved highest accuracy of 95%** 

There are 10 types of classes we have taken to train the model

![types of classes paddy (Small)](https://user-images.githubusercontent.com/91750738/199874771-77462fae-ef06-4640-b9d4-85e39a895901.jpg)

We have mainly used 2 models:
* Moblienet


a) model 1 : Accuracy = 74.02%

These are the predicted output by using mobilenet(model_1) model


<img src="mobilenet.png">



* VGG16


a)	VGG16 without finetuning (model 2) : Accuracy = 90.20%


b)	VGG16 with finetuning (model 3) : Accuracy = 93.23%


c)	VGG16 with finetuning and Data Augmentation (model 4) : Accuracy = 95.53%


So our model_4 gives highest accuracy so we will be selecting model_4 as the model to predict the data

These will be prediction for 100 images by using VGG16(model_4)

<img src="VGG16(data_Augmented).png">
