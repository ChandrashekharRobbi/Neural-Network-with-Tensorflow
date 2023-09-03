[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChandrashekharRobbi/Convolutional-Neural-Network-or-Neural-Network-with-Tensorflow/blob/main/Regression%20Neural%20Networks/Regression%20Problems/Medical%20Insurance/medical_insurance.ipynb)

# 🩺 Medical Insurance Prediction

In this project, I've delved into the realm of medical insurance costs. Leveraging a dataset sourced from Kaggle, my primary objective is to predict insurance charges based on specific parameters.

If the goal is to predict a numerical value, it's a **Regression Problem**, and that's precisely what I tackled here!

## 🚀 Project Breakdown:
### 1️⃣ Understanding & Preprocessing the Data

Gaining a deep understanding of the data is crucial. Not only does it shed light on the available parameters/features, but visualizations also provide richer insights.

I've optimized data preprocessing, employing the `pd.get_dummies()` method for one-hot encoding.

![Data Visualization](https://user-images.githubusercontent.com/91750738/178977384-2d758c36-8c3d-4d24-9e44-6a6a5f00bfc1.png)
![Preprocessed Data](https://user-images.githubusercontent.com/91750738/178978479-19fffffe-2405-49ae-a473-5e856b8ba51f.png)

### 2️⃣ Crafting the Baseline Model

I embarked on the modeling journey with a baseline model, comprising just two dense layers. Always best to start simple and then refine!

![Baseline Model](https://user-images.githubusercontent.com/91750738/178977877-360284d8-a923-4edd-a2f7-377e4293ba74.png)

### 3️⃣ Evaluating the Model

Here, I assessed the model's prowess in learning patterns and its precision in predicting insurance charges. The chosen metric for evaluation? Mean Absolute Error (MAE).

![Model Evaluation](https://user-images.githubusercontent.com/91750738/178978519-096657ec-69a5-4279-a122-953a76409335.png)

### 4️⃣ Refining & Improving the Model

A model can always be better! Some strategies I adopted include:
- Introducing additional layers.
- Experimenting with different activation functions.
- Adjusting the learning rate.

## 🌐 Future Directions:
I'm continuously seeking ways to enhance the model further. Your feedback and suggestions are invaluable in this journey!
