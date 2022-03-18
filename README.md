# AntClassifier
Сomputer vision model to classify images of several species of ants using transfer learning.
# Data
The model is trained to classify 4 species of ants. We have about a hundred images for each species, which is not enough to teach the model from scratch.
# Project
Using a finished resnet18 network with pre-trained weights, replacing the output layer and freeze the weights of all other layers. Target metric - accuracy.