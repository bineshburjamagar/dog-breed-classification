🐶End-to-end Multi-Class Dog Breed
List item
List item
Classification

This notebook builds an end-to-end multi-class image classifier using Teserflow 2.0 and TensorFlow Hub.

1. Problem
Identifying the breed of the dog.

When I'm sitting at the cafe and I take a photo of a dog, I want to know what breed of dog it is.

2. Data
The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data

3. Evaluation
The evaluation is a file with prediction probabilities for each dog hreed of each test image

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

4. Features
Some information about the data:

We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
There are 120 breeds of dogs (this means there are 120 different classes).
There are around 10,000+ images in the training set (these images have labels)
There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them)
