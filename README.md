# SC1015-Mini-Project-BCF1-Group-04

## About 
1. Our project seeks to conduct landscape detection using Intel Image Dataset to detect 6 types of landscape: Sea, Glacier, Forest, Buildings, Mountain and Streets.
2. We will be taking you through the process of creating and modifying our CNN model to analyse the changes in accuracy of our model due to the respective changes.

## Contributors 
- Keith 
- Angie 
- John 

## Problem Statement: 
In today’s context, we are dealing with a vast amount of unstructured image data from cameras and sensors. Image classification is one of the fundamental problems in the field of computer vision.

By using knowledge from SC1015 and convoluted neural networks, we seek to apply image classification on landscape images to identify 6 landscapes, namely Sea, Glacier, Forest, Buildings, Mountain and Street.

## Model Used 
- Convolution Neural Network (CNN)
- Relu function and dropout technique

## Conclusion
- An image classification model can be created using CNN. Though this model may have issues such as overfitting or certain types of images which are more prominently misclassified, it is possible for us to optimise the CNN model.
- Firstly, we can improve accuracy by increasing the no. of epochs. 
- Secondly, we can do this is by introducing a dropout layer. 
- Thirdly, accuracy can be further raised by  increasing the number of convolution blocks. This also addressed the issue of overfitting to a certain extent, by curbing the increase in validation loss at higher number of epochs. 
- Lastly, to further address overfitting, we can implement a controlled learning rate, which has shown to cause validation loss to decrease and stay constant up until 64 epochs. 

## What we have learned from this project
- Handling imbalance data 
- Handling image data 
- Neural Networks, Keras and Tensorflow 
- Collaborating using Github
- Learning rate alpha and gradient descent
- Data Science and processing
- Read and process image data 
- Convoluted Neural Network Model
- Address overfitting in processing image data
- Use of activation function RELU
- Reduce accuracy loss and validation loss


## References
- [....]
- https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
- https://github.com/nicklimmm/movie-analysis
- https://datascience.stackexchange.com/questions/109905/cannot-achieve-good-result-while-transfer-learning-cifar-10-on-resnet50-keras
- https://stackoverflow.com/questions/39517431/should-we-do-learning-rate-decay-for-adam-optimizer
