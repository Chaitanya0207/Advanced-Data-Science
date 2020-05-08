****************************************************************************************************************************************

## Assignment 4:

## Objective - 

•	The GAN consists of a Generator and Discriminator that works as follows - The generator takes in random numbers/noise and returns an image.This generated image is fed into the discriminator alongside a stream of images taken from the actual, ground-truth dataset. The discriminator takes in both real and fake images and returns probabilities, a number between 0 and 1, with 1 representing a prediction of authenticity and 0 representing fake.Two neural networks contest with each other in a game (in the sense of game theory, often but not always in the form of a zero-sum game). Given a training set, this technique learns to generate new data with the same statistics as the training set. For example, a GAN trained on photographs can generate new photographs that look at least superficially authentic to human observers, having many realistic characteristics.One neural network, called the generator, generates new data instances, while the other, the discriminator, evaluates them for authenticity; i.e. the discriminator decides whether each instance of data that it reviews belongs to the actual training dataset or not. 

•	Dataset : Celebrity images dataset consists of 100,000 images - 100k of 128x128 celebrities' images. Cropped faces from CelebA dataset. Link from kaggle - https://www.kaggle.com/greg115/celebrities-100k/activity

