# Dog Breed Classifier
A Classifier to distinguish between 133 different dog breeds.

## Project Overview

Over the past few years, development in Artificial Intelligence and Machine Learning has improved our lives in many different ways. Its impact has been far and wide, in both industry and research, and has allowed us to solve problems that were considered impossible just a few years ago. One of the biggest winners of this new AI revolution has been the field of Computer Vision. 

In this project, Convolutional Neural Networks and a Haar Cascades OpenCV detector is used to distinguish between various dog breeds and humans. The application is first successfully able to distinguish between a dog and a human and then classifies detected dog images based on it’s breed, and human images as the dog breed that the human looks most similar to. 


## Problem Statement

The goal of the project is to build an image classifier, which can perform a series of tasks as follows.

* Given an input image of either a dog or a person, the application should classify whether it is a dog or a human. In other words, it should calculate the probability that it is a dog.

• If the image is of a dog, the application should classify, which dog breed it belongs to from a number of possible classes. This may be extended to include mixed breed dogs. In a mathematical sense, given an image the CNN should output the probability that the image belongs to a particular breed of dog.

• If the input image was of a human, the CNN should output the dog breed that the human most resembles.
    
## Datasets used

The datasets used for this project were provided by Udacity. They are linked below

1. [Dog Dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
2. [Human Dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

I also used a few additional images and these can be found at:

1. Mona Lisa: http://lookatherbeautifulface.blogspot.com/2010/08/one-of-most-famous-female-faces-in.html       
2. Albert Einstein: https://www.bbc.com/news/health-23665502
3. Bruce Lee: https://www.sporcle.com/games/MSUKent/50-faces
4. German Shepherd: https://www.britannica.com/animal/dog
5. Pug: https://www.smithsonianmag.com/smart-news/excessive-vitamin-d-pet-food-may-be-making-dogs-sick-180970963/
6. Golder Retreiver: https://santansun.com/2018/11/06/valley-fever-storm-brewing-for-chandler-dog-owners/

## Software Requirements:
The project was created on a system using the [Anaconda](https://www.anaconda.com/) Distribution. In addition to those it also use PyTorch 1.4+ and OpenCV v3.4+.
