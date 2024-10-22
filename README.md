# Alphabet_Recognition_Gestures
This deep learning application in python recognizes alphabet through gestures captured real time on a webcam. The user is allowed to write the alphabet on the screen using an object-of-interest.
# Resource Requirements
The code is in Python (version 3.6 or higher). You also need to install OpenCV(4.4.0 version) and Keras (2.1.3 version) and tensorflow (2.3.1) libraries.
# Data Description 
A popular demonstration of the capability of deep learning techniques is object recognition in image data.

The "Extended Hello World" of object recognition for machine learning and deep learning is the [EMNIST](https://www.kaggle.com/crawford/emnist) dataset for handwritten letters recognition. It is an extended version of the [MNIST](https://en.wikipedia.org/wiki/MNIST_database) dataset.

A set of sample images is shown below.

![e](https://user-images.githubusercontent.com/48173479/104183572-288a8300-5438-11eb-8fda-2bad7c713157.jpg)


![a](https://user-images.githubusercontent.com/48173479/104183726-69829780-5438-11eb-94fd-41143b3f5fb0.jpg)

A Multilayer Perceptron (MLP) model as well as a Convolutional Neural Network (CNN) model using Keras library. The predictions of both the models are shown on the screen in real time.  

The Test accuracies were as follows:  

->MLP Test Accuracy: 91.7%  
->CNN Test Accuracy: 93.1%  

#Execution    
Execute mlp_model_builder.py for bulding the Model architecture using Multilayer Perceptron Network

Execute cnn_model_builder.py for building the Model architecture using Convolutional Neural Network.

Execute alpha_recognition.py to run the Alphabet detection code.  

Use a Blue bottle cap to Draw the letters on the Screen   
  

