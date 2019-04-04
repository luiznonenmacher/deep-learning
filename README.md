# dog_breed_classification

## Introduction

This repository contains the final project of Udacity's Machine Learning Engineer Nanodegree Deep Learning section. The objective of this project is to take an image and detect if it is a human, a dog or none of the above. If it is a dog, it will try to guess the dog breed and if it is a human, it will output the dog breed that the humans look more alike.

The classification will de done by using two CNNs, one trained from scratch and another built using Transfer Learning, import the [VGG-16](https://keras.io/applications/) model from Keras Applications.

### Instructions

Given the size limitations, to run this model you should download some data:

1. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`. 

2. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

3. Donwload the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.

After downloading this data, you should open the notebook and execute the code.
