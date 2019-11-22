# DogBreedCNN

In this project, we will build a pipeline to process real-world, user-supplied images that given an image of a dog, will detect its resembling breed. If supplied an image of a human, the code will identify the resembling dog breed.

In order to achieve the aforementioned goals of this project we will make use of state-of-the-art Convolutional Neural Network models for the classification of dog breeds. The Keras library is used to tackle this task. The code was developed using Jupyter Notebooks and Python.

## Analysis

The results of this project can be found in the following blog post:
https://medium.com/@kremmydosporos/dog-breed-prediction-using-convolutional-neural-networks-d11a0a391fdf

## Libraries used

Following libraries were used:
- sklearn 
- keras
- numpy
- glob
- cv2
- random
- matplotlib
- ResNet50
- VGG16
- tdqm
- PIL

## Files
The files in this project are the following:
- bottleneck_features : These are the bottleneck features for the the ResNet50 networks
- haarcascades : A human detector pulled from OpenCV's implementation https://github.com/opencv/opencv/tree/master/data/haarcascades
- images : Some sample images used in the notebook 
- requirements : The environment requirements for different environments
- saved_models : Saved ML models
-LICENSE : the license of this project
- README.md : the readme file of this project
- dog_app.html : an html export of the jupyter notebook
- dog_app.ipynb : the jupyter notebook that holds the implementation of this project
- extract_bottleneck_features.py - helper python file to extract bottlenect features

## Acknowledgements

This project was developed as part of Udacity's Data Scientist Nanodegree capstone and makes use of material provided by Udacity.
