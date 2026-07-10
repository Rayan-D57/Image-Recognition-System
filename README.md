# Image Recognition System - Project Documentation

## Overview
This project showcases an end-to-end image classification pipeline. I have successfully trained a custom deep learning model to recognize and classify three distinct classes using Google's Teachable Machine, followed by deploying the model locally using Python.

##  Project Lifecycle
The project was developed through the following stages:

1.  Model Training: I trained a model using Google Teachable Machine with three specific categories (classes). The model was evaluated for accuracy during the training process.
2.  Model Export: The trained model was exported in the TensorFlow Keras (`.h5`) format.
3.  Local Implementation: I developed a Python script that loads the .h5 model and the labels.txt file to perform real-time image inference.
4.  Testing: The system was tested locally in VS Code to ensure accurate class prediction and confidence scoring.

##  Project Evidence

### 1. Training Phase (Google Teachable Machine)
*This image displays the model training process on the Teachable Machine platform with my three defined classes.*
<img src="Tranining Phase" width="500">

### 2. Testing Phase (Python/VS Code Output)
*This image shows the Python script running locally and successfully predicting the class of an input image with its confidence score.*
![Testing Phase](Tranining Phase)

