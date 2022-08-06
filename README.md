# Hand-Gesture-Recognition

# Problem Statement:
To create a hand gesture recognition model using images


# About the dataset:
The dataset contains different hand gestures.It consists of 10 different hand gestures like palm,fist,fist moved,thumb etc... of 10 different subjects.Every root folder (00, 01,…) contains the infrared images of one subject. The folder name is the identifier of each different subject.

# Toolkit:
1) CNN:
A Convolutional Neural Network is a special class of neural networks that are built with the ability to extract unique features from image data.Reducing the size of the numerical representation sent to the CNN is done via the convolution operation. This process is vital so that only features that are important in classifying an image are sent to the neural network. Apart from improving the accuracy of the network, this also ensures that minimal compute resources are used in training the network.Here, a CNN model is bulit for recognising the hand gestures.
2) ANN:
ANN models are the extreme simplification of human neural systems. An ANN comprises of computational units analogous to that of the neurons of the biological nervous system known as artificial neurons. Mainly, the ANN model constitutes of three layers, viz., input, hidden, and output.The ANN may be useful in solving different engineering and science problems.Here, an ANN model from sklearn is used.

# Testing and Evaluation
The testing and training was done on Jupyter Notebook.
A CNN model was ceated whose accuracy was 99.95%
An ANN model from sklearn was created whose accuracy was close to 86%
