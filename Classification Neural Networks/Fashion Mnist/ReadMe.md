[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChandrashekharRobbi/Convolutional-Neural-Network-or-Neural-Network-with-Tensorflow/blob/main/Classification%20Neural%20Networks/Fashion%20Mnist/Fashion_Mnist.ipynb)
# Fashion Mnist

**Category:** **Multi-Class Classification**

Fashion-MNIST is a dataset that features Zalando's article images—comprising a training set of 60,000 examples and a test set of 10,000 examples. Each instance is a 28x28 grayscale image, mapped with a label from 10 distinct classes. Fashion-MNIST is envisioned to act as a seamless drop-in substitute for the original MNIST dataset, primarily for benchmarking machine learning models. It retains the identical image size and the format of training/testing split as the traditional MNIST.

### Classes Overview:

![dataset-cover](https://user-images.githubusercontent.com/91750738/178717492-52aca905-529e-4a39-aa78-dfdd8675eba0.png)

Throughout this project, I've adhered to a specific set of steps, namely:

## 1. Visualize the Data

![image](https://user-images.githubusercontent.com/91750738/178717983-046610b5-fbee-4925-98c8-331f661b9119.png)

## 2. Construct a Baseline Model
   - Designing the model
   - Compiling the model
   - Training the model

## 3. Evaluate the Model

To assess the proficiency of our multi-class classification model, I:
- Analyzed its performance using various classification metrics, like the confusion matrix.
  
![image](https://user-images.githubusercontent.com/91750738/178720482-62d28379-1df1-450f-b913-149a5cfa5130.png)

- Sampled some of its predictions (visually represented below)

![image](https://user-images.githubusercontent.com/91750738/178720548-af6270b6-d638-431c-8d23-fcb1359d4695.png)

- Suggested potential enhancements (either by prolonging training or modifying its architecture)
- Saved and exported the model for potential application integration

## 4. Refinement of the Model

There are myriad ways to enhance a model. In this project, I've experimented with:
- Determining and implementing the optimal **learning rate**
- Normalizing the dataset
- Introducing additional layers to the architecture

In conclusion, the refined model confidently classifies images from the Fashion Mnist test dataset with an accuracy surpassing **80%**.

### 📢 Upcoming
I'm excited to announce that a user-friendly UI for this model is in the pipeline and will be launched soon. Stay tuned!
