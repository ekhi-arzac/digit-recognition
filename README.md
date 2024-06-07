# Handwritten Digit Recognition with Convolutional Neural Network

This project demonstrates how to build and train a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset  with TensorFlow.

## Project Overview

The MNIST dataset contains 70,000 grayscale images of handwritten digits (0-9), each of size 28x28 pixels. This project uses a CNN to classify these images into one of the 10 digit classes.
The CNN model consists of two convolutional layers, each followed by a max-pooling layer, and two fully connected layers. The model is trained using the Adam optimizer and the categorical crossentropy loss function. The model is trained for 10 epochs with a batch size of 32. The model achieves an accuracy of 99.2% on the test set.

## Project Structure

- `DigitRecognition.ipynb`: Jupyter notebook that contains the complete code for loading data, preprocessing, building the model, training, evaluating, and visualizing the results along some small explanations.
- `README.md`: This file, providing an overview and instructions for the project.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- TensorFlow


## How to run the project
Instructions are specified in the notebook, it is recommended to create a virtual environment, as to avoid any conflicts with the dependencies. 

## Bibliography
- CNNs for Image Classification, TensorFlow Documentation, https://www.tensorflow.org/tutorials/images/cnn
- MNIST Dataset, Yann LeCun, Corinna Cortes, Christopher J.C. Burges, http://yann.lecun.com/exdb/mnist/ 
