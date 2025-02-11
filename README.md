# Handwritten-digits-recognition

## Overview  
This project uses the Mnist digits dataset to train a CNN model to classify the handwritten numerals.
The model is optimized using Keras Tuner for hyperparameter tuning, achieving high accuracy on both the training and test sets.  

## Dataset  

The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits (0-9), each represented as a 28x28 grayscale image.  

## Model Architecture  

The CNN model consists of:  
- Two Convolutional Layers   
- Two MaxPooling Layers   
- Flatten Layer  
- Dense Fully Connected Layer 
- Output Layer   

## Hyperparameter Tuning  

The model is optimized using Keras Tuner with a Random Search approach. The hyperparameters used are: 
- Number of filters in the Conv2D layers  
- Kernel size   
- Number of neurons in the Dense layer  
- Learning rate of the Adam optimizer  

## Model Performance  
The following accuracies were obtained when tested with the training and testing data accuracy:
- Training Accuracy: 99.63%  
- Training Loss: 0.0119  
- Test Accuracy: 98.74%  

## Features  

 Data Preprocessing- (Normalization, Reshaping)  
 Hyperparameter Tuning with Keras Tuner  
 Visualization of CNN Layer Activations  
 Real-Time Image Prediction- (User can upload an image for model inference)  

   

