# Fashion-MNIST-Classification-in-R

This is one part of a final project submitted for the STAT 154 "Modern Statistical Prediction and Machine Learning" class I completed at UC Berkeley.

The Fashion MNIST dataset is a popular and novel image dataset used for benchmarking machine learning models and training classification algorithms.

The dataset contains 18,000 different 28×28 grayscale images of clothing, each with a label of either shoes, shirt, or pants (6000 of each). If we stack the features into a single vector, we can transform each of these observations into a single 28∗28 = 784 dimensional vector. 

Our tasks are as follows:

#### Data exploration and dimension reduction

In this section, you will experiment with representing the images in fewer dimensions than 28∗28 = 784. You can use any of the various dimension reduction techniques introduced in class. How can you visualize these lower dimensional representations as images? How small of dimensionality can you use and still visually distinguish images from different classes?

#### Classification task

##### Binary classification

In this section, you should use the techniques learned in class to develop a model for binary classification of the images. More specifically, you should split up the data into different pairs of classes, and fit several binary classification models. For example, you should develop a model to predict shoes vs shirts, shoes vs pants, and pants vs shirts. Remember that you should try several different methods, and use model selection methods to determine which model is best. You should also be sure to keep a held-out test set to evaluate the performance of your model.

##### Multiclass classification

In this section, you will develop a model to classify all three classes simultaneously. You should again try several different methods, and use model selection methods to determine which model is best. You should also be sure to keep a held-out test set to evaluate the performance of your model. (Side question: how could you use the binary models from the previous section to develop a multiclass classifier?)
