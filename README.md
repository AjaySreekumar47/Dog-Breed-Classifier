End-to-End Multi-class Dog Breed Classification
This notebook builds an end to end multi-class image classifier using Tensorflow 2.0 and Tensorflow Hub.

1. Problem
Identifying the breed of a dog given an image of the dog.

2. Data
The data we're using is from Kaggle's dog breed identification competition.

https://kaggle.com/c/dog-breed-identification/data

3. Evaluation
The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

4. Features
Some information about the data:

We are dealing with images (unstructured data) so, its probably best that we use Deep Learning / Transfer Learning.
There are 120 breeds of dogs (meaning 120 different classes)
There are around 10,000+ images in the training set (These images have labels)
There are 10,000+ images in the test set. (No labels in these images as we need to predict them.)
