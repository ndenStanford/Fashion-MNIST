# Fashion MNIST

This repo contains a classifier on Fashion-MNIST dataset (https://github.com/zalandoresearch/fashion-mnist). We attempt to build the classigifer with highest accuracy while using the smallest number of training label possible. 

# Concept

We levarage the power of weak supervision (https://www.snorkel.org/blog/weak-supervision) to generate large number of labels by using labelling functions built from a small subset of labeled dataset. 

## Labelling Functions
- KNN on raw pixel
- KNN on HOG feature extraction 
- SVM on HOG feature extraction 

## Final Model
- Small CNN network due to a limitation in computation resources and time. 