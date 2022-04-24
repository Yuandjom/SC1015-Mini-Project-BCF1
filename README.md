# SC1015-Mini-Project-BCF1-Group-04
(https://www.kaggle.com/datasets/puneet6060/intel-image-classification)


## About 
1. Our project seeks to conduct landscape detection using Intel Image Dataset to detect 6 types of landscape: Mountain, Streets, Sea, Glacier, Buildings and Forest. 

2. We will be taking you through the process of creating and modifying our CNN model. As we make modifications to our model, we will analyse the changes in accuracy of our model.

## Landscape 
![image](https://user-images.githubusercontent.com/69751989/164974919-8205b2bf-2c61-4487-ae2d-9fe5702408aa.png)
![image](https://user-images.githubusercontent.com/69751989/164975022-8fece914-aa22-43ab-9b4e-5bc080990915.png)
![image](https://user-images.githubusercontent.com/69751989/164975027-7f587860-98f4-416a-ab41-bf0707703820.png)
![image](https://user-images.githubusercontent.com/69751989/164975036-3a044e6d-f39e-46b1-920f-c33f1cf9d3ea.png)
![image](https://user-images.githubusercontent.com/69751989/164975045-f1fc6643-2903-431b-ae7d-fce8e8c63659.png)
![image](https://user-images.githubusercontent.com/69751989/164975055-27cda852-28e9-45c9-8623-cbb5c62d6a15.png)

## Contributors 
- Angie -> Problem statement, Data preparation, Data extraction and Data visualisation
- Keith -> CNN model: Compilation of model, Accuracy and Validation Accuracy/Loss, Model evaluation
- John -> CNN model: Training and Testing of models, Fine tuning hyperparameter for optimiser and Data visualisation 

## Problem Statement: 
In today’s context, we are dealing with a vast amount of unstructured image data from cameras and sensors. Image classification is one of the fundamental problems in the field of computer vision.

By using knowledge from SC1015 and convoluted neural networks, we seek to apply image classification on landscape images to identify 6 landscapes, namely Sea, Glacier, Forest, Buildings, Mountain and Street.
! 

## Model Used 
- Convolution Neural Network (CNN) with 20 epochs 
    - Controlled Learning rate
    - Dropout Layers
- Convolution Neural Network (CNN) with 64 epochs 
    - Controlled Learning rate
    - Dropout Layers
   
## Conclusion
- An image classification model can be created using CNN. Though this model may have issues such as overfitting or certain types of images which are more prominently misclassified, it is possible for us to optimise the CNN model.
- Firstly, we can improve accuracy by increasing the no. of epochs. 
- Secondly, we can do this is by introducing a dropout layer. 
- Thirdly, accuracy can be further raised by  increasing the number of convolution blocks with dropout layers. This also addressed the issue of overfitting to a certain extent, by curbing the increase in validation loss at higher number of epochs. 
- Lastly, to further address overfitting from excess epochs, we can implement a controlled learning rate, which has shown to cause validation loss to decrease

## What we have learned from this project
- Collaboration using Github
- Handling imbalanced image data 
- Read and process image data
- Neural Networks, Keras and Tensorflow
- Convoluted Neural Network Model
- Fine tuning the learning rate for the optismer 
- Address overfitting in processing image data
- Use of activation function RELU
- Reduce accuracy loss and validation loss


## References
- https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
- https://datascience.stackexchange.com/questions/109905/cannot-achieve-good-result-while-transfer-learning-cifar-10-on-resnet50-keras
- https://stats.stackexchange.com/questions/147850/are-pooling-layers-added-before-or-after-dropout-layers
- https://datascience.stackexchange.com/questions/25267/keras-difference-beetween-val-loss-and-loss-during-training
- https://stackoverflow.com/questions/39517431/should-we-do-learning-rate-decay-for-adam-optimizer
- https://www.kaggle.com/code/vincee/intel-image-classification-cnn-keras
- https://towardsdatascience.com/applied-deep-learning-part-4-convolutional-neural-networks-584bc134c1e2
- https://towardsdatascience.com/a-beginners-guide-to-convolutional-neural-networks-cnns-14649dbddce8
- https://viso.ai/computer-vision/image-classification/
