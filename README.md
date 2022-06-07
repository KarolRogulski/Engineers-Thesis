# Engineer's Thesis

## Overview

This is my engineer's thesis project.

### Goal
Find the best learning rate for existing algorithms, 
and then check how the change in the size of the training set affects their accuracy

### Stanford Dogs Dataset
Briard           |   Great Pyrenees         | Samoyed
:-------------------------:|:-------------------------:|:-------------------------:
![alt text](https://github.com/KarolRogulski/Engineers-Thesis/blob/master/img/dog1.png?raw=true) |  ![alt text](https://github.com/KarolRogulski/Engineers-Thesis/blob/master/img/dog2.png?raw=true)| ![alt text](https://github.com/KarolRogulski/Engineers-Thesis/blob/master/img/dog3.png?raw=true)



The Stanford Dogs dataset contains 20,580 images of 120 breeds of dogs from around the world. 
This dataset has been built using images and annotation from ImageNet for the task of fine-grained image categorization. </br>
[Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/)

### Models
* MobileNet
* Xception
* Inception V3
* VGG19

## Development process
1. Preprocess dataset (create subsets containing the appropriate classes and distribution matrix).
2. Test different values of learning rate and find the best.
3. Using the best learning rate train 5 times every algorithm using different sizes of training set.
4. Create results visualizations

