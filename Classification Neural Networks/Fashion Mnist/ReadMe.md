# Fashion Mnist

This project comes under **Multi-Class Classification**



Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. We intend Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.


The classes look some thing like this 


![dataset-cover](https://user-images.githubusercontent.com/91750738/178717492-52aca905-529e-4a39-aa78-dfdd8675eba0.png)



I have followed certain steps which include:

# 1. Visualize the data


![image](https://user-images.githubusercontent.com/91750738/178717983-046610b5-fbee-4925-98c8-331f661b9119.png)

# 2. Create Baseline Model
   * Create the model 
   * Compile the model 
   * Fit the model

# 3. Evaluating the model

To evaluate our multi class classification model we could do:

* Evaluate it's peformance using other classification metrices (such as confusion matrix)

![image](https://user-images.githubusercontent.com/91750738/178720482-62d28379-1df1-450f-b913-149a5cfa5130.png)

* Access some of its predictions ( through visualization )

![image](https://user-images.githubusercontent.com/91750738/178720548-af6270b6-d638-431c-8d23-fcb1359d4695.png)

* Improve its results ( by training it for longer or changing the architecture)
* Save and export it for use in an application


# 4.Improve the model

Model can be imporved many ways but the methods i have tried:
* Training the model by finding the ideal **learning rate**
* Converting the data into the normalized form
* Adding more layers



At the last our model is able to predict the images of  Fashion Mnist test dataset with the accuracy of above **80%**  :)



