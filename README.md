# Melanoma Detection Using Convolutional Neural Network
In this assignment we are building a CNN model which can accurate detect Melanoma by processing and learning the images collected in a dataset International Skin Imaging Collaboration (ISIC)
For this assignment we will following below steps -
a. Importing required libraries TensorFlow, Keras
b. Importing Train and Test dataset
c. Creating base model from Training dataset
d. Based on observations apply image augmentation techniques and handle class imbalance
e. Evaluate Model and check test results


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
Melanoma is a type of cancer that accounts for 75% of skin cancer deaths. Early diagnosis of this cancer from the images could prove to be effective in treating this cancer. Building a CNN model could reduce manual effort needed in diagnosis.
Dataset used for this has 2357 images of both malignant and benign oncological diseases and were formed from the ISIC (International Skin Imaging Collaboration). We will be using different hyperparameters to build the model e.g. We will check model with and without dropouts. We will check for epochs 20, 30 and 50 etc.


## Conclusions
- Base CNN model did not have any dropouts layer or augmentation techniques used. This CNN model overfits the training data giving poor results on the validation set.
- After this we apply different domain specific augmentation techniques like Random Flip, Random Rotation, Zoom, Contrast, Brightness and Random Cropping
- These augmentation techniques prevent from Model being overfitted with comparable Training and Validation accuracies.
- However, the accuracies are still around 50% which is only slightly better than a random guess.
- We also notice that there is class imbalance present
- After correcting class imbalance, Training and Validation accuracies have improved significantly.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- TensorFlow - 2.17.0
- Numpy 1.26.4
- PIL 9.4.0


## Acknowledgements
- This assignment is part of curriculum for postgraduate program by IIIT-B in Artificial Intelligence and Machine Learning.
- This project uses concepts learned from below modules
  1. Introduction to Neural Network
  2. Convolutional Neural Network


## Contact
Created by [@kaspatekajal] - feel free to contact me!
