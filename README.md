# Comparing Accuracy of CNN Models to Identify Dog Breeds
Classifying dogs and their breeds from images using CNN Architecture Models: ResNet, AlexNet, and VGG, and ultimately comparing accuracy.

## Table Of Contents

### Programming Project
Determine which CNN architecture model works best at classifying images of dogs and their breeds.

### Objectives
First: Identify which pet images are of dogs and which pet images are not of dogs.
Second: Classify the breeds of dogs, for the images that are of dogs.

### Results
CNN Model Architectures: ResNet, AlexNet, VGG
% Not-a-dog Correct: ResNet(90%), AlexNet(100%), VGG(100%)
% Dogs Correct: ResNet(100%), AlexNet(100%), VGG(100%)
% Breeds Correct: ResNet(90%), AlexNet(80%), VGG(93.3%)
% Match Labels: ResNet(82.5%), AlexNet(75%), VGG(87.5%)

### Discussion
For the first objective, both VGG and AlexNet correctly identify images of "dogs" and "not-a-dog" 100% of the time.
For the second objective, VGG provides the best solution because it classifies the correct breed of dog over 90% of the time.
Overall, model VGG was the one that was able to classify "dogs" and "not-a-dog" with 100% accuracy and had the best performance regarding breed classification with 93.3% accuracy.

## Dependencies
Each directory has a `requirements.txt` describing the minimal dependencies required to run the notebooks in that directory.

### pip
To install these dependencies with pip, you can issue `pip3 install -r requirements.txt`.

### Project
Project Submitted to Udacity AI Programming with Python Nanodegree.
Use a Pre-trained Image Classifier to Identify Dog Breeds.
* [Notes:](https://github.com/udacity/AIPND-revision/tree/master/notes "Notes")
