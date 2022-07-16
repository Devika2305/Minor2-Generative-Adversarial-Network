# Minor2-Generative-Adversarial-Network

There are two models called Discriminator and the Generator. Discriminator models aim is to maximize the probability of predicting the real image. The training procedure for the Generator model is to maximize the probability of the discriminative model making a mistake.

## Objective:
To train a Generative adversarial network on images of cars to learn the features and generate new fake designs which seem real to a human.

To design the Critic model to extract the the features of the Cars using the Hammer-Head Architect.

To design the Generator model to generate the new photo realistic images using the Hammer-Head design by learning individual features.

## Dataset:
Dataset used is the Cars dataset that contains 16,185 images of 196 classes of cars, out of which we sample 1280 images to train out Critic Model.

Dimension of Images is 3x64x64

![image](https://user-images.githubusercontent.com/57962316/179347456-3708d4dd-473d-4736-8230-f5a78207f00f.png)


## Architecture Design:

![image](https://user-images.githubusercontent.com/57962316/179347488-bd471fbd-3822-4125-95b5-3130bd72c031.png)


## Result:
![image](https://user-images.githubusercontent.com/57962316/179347504-e3fa8569-10fd-4d5f-afe6-b38a63bcbf57.png)
