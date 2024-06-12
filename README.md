# Handwritten-Digit-Recognition
Handwritten digit recognition, The task involves identifying handwritten digits from an image and classifying them into  the corresponding numerical values. In this project, we have developed a Flask-based application that  recognizes handwritten digits using a pre-trained machine learning model.
Objective:

The objective of this project is to build a machine learning model that can accurately recognize handwritten 
digits and to develop a Flask-based web application that utilizes the model to recognize digits entered by users.

Methodology:

We used the MNIST dataset for training and testing our machine learning model. This dataset consists of 
60,000 training images and 10,000 test images of handwritten digits from 0 to 9. We used a convolutional 
neural network (CNN) architecture to train our model on this dataset.

Once the model was trained and tested, we saved it as a serialized object using the joblib library. 
We then developed a Flask-based web application that allows users to draw a digit using their mouse 
or touchscreen and submit the image to the model for recognition.

Results:
Our machine learning model achieved an accuracy of 99.1% on the MNIST test set. When integrated with the 
Flask application, the model is able to accurately recognize handwritten digits drawn by users in real-time.

Technology Overview:

Machine Learning – Machine learning is a subfield of artificial intelligence that enables machines to learn 
from data, without being explicitly programmed. In this project, we used machine learning algorithms to 
recognize handwritten digits.

Convolutional Neural Networks – Convolutional Neural Networks (CNNs) are a class of deep neural networks 
commonly used in image processing and computer vision tasks. CNNs are designed to recognize visual patterns 
directly from pixel images, making them well-suited for tasks like image classification and object detection.

Flask – Flask is a lightweight web framework that enables the development of web applications in Python. 
In this project, we used Flask to develop a web application that allows users to input handwritten digits 
and receive predictions from the trained machine learning model.

MNIST Dataset – The MNIST dataset is a large database of handwritten digits commonly used for training and 
testing machine learning models. The dataset consists of 60,000 training images and 10,000 test images of 
handwritten digits from 0 to 9.

Joblib – Joblib is a library for Python that enables the efficient serialization and deserialization of Python 
objects. In this project, we used Joblib to save and load the trained machine learning model.
