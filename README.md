# Mine_prediction
![images-_9_](https://user-images.githubusercontent.com/111365771/222960326-41e7ae6b-61f6-4cb9-9b38-ad289b13c601.jpg)

This project aims to classify sonar signals into two categories: rocks and mines using the oneDNN 

# Introduction:

Sonar data is widely used in many applications such as underwater communication and navigation systems. In this project, we aim to develop a machine learning model using the oneDNN (Deep Neural Network) sequential model to classify sonar signals into two categories: rocks and mines. The model is trained using a dataset containing sonar 
readings and their corresponding labels.

# About oneAPI and oneDNN:
![download](https://user-images.githubusercontent.com/111365771/222960387-f6aa6eb8-ef74-44aa-8576-78f6b78c29a8.jpg)

oneAPI is an open-source software toolkit developed by Intel that simplifies the development of high-performance, heterogeneous applications. It allows developers to write code that can run efficiently on a variety of architectures, including CPUs, GPUs, and FPGAs. oneDNN (Deep Neural Network) is a part of oneAPI and is an optimized library for deep learning. It provides highly optimized building blocks for neural network models that run efficiently on a variety of hardware platforms.

# oneDNN Sequential Model:

The oneDNN sequential model is a type of neural network model that consists of several layers of neurons. Each layer processes the output of the previous layer to produce a new output. The model uses the backpropagation algorithm to adjust the weights of the neurons during training to minimize the difference between the predicted 
and actual output. In this project, we used a oneDNN sequential model with several dense layers to classify the sonar signals.

# Results:

We trained the oneDNN sequential model on the sonar dataset and achieved an accuracy of 88% on the test set. The model was able to classify sonar signals into rocks and mines with high accuracy, which demonstrates the effectiveness of using deep learning techniques for sonar signal classification. The high accuracy of the model makes it suitable for use in real-world applications such as underwater navigation and communication systems.

In conclusion, the oneDNN sequential model is a powerful tool for developing machine learning models for sonar signal classification. Its ability to efficiently run on various hardware platforms makes it suitable for use in a wide range of applications.
