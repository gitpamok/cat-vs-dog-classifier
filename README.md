# cat-vs-dog-classifier

**Problem statement** :

In this project, I have implemented Convolution Neural Network(CNN) Classifier for Classifying dog and cat images. The Total number of images available for training is 25,000 and final testing is done on seperate 10,000 images.

This problem statement and dataset is taken from this [Kaggle](https://www.kaggle.com/c/dogs-vs-cats) competition.

**Convolutional Neural Network**

In deep learning, a convolutional neural network is a class of deep neural networks, most commonly applied to analyzing visual imagery. 
 **Brief Overview of the Models implemented**:
 1. **Model_1** :A CNN model containing 7 layers (3 convolutional, 1 flatten, and 3 dense) and is designed to handle binary classification task of cat and dog image classification.
 2. **Model_2** : Using the pretrained model VGG16
 3. **Model_3** : This model uses a pre-trained VGG16 network as a base, with selective fine-tuning of layers starting from 'block5_conv1'. It adds a custom top layer for binary classification and compiles the model with an appropriate loss function and optimizer for fine-tuning.
