# Assignment 2 - Convolutional Neural Networks

### This folder contains the code for all the 3 parts of Assignment 2 of the course CS6910 - Fundamentals of DL.

### Group members: 
Karthik S - ME18B149
Aravint Annamalai - EE18B125

[Problem Statement](https://wandb.ai/miteshk/assignments/reports/Assignment-2--Vmlldzo0NjA1MTU)

[Report Link(wandb)](https://wandb.ai/kodikarthik21/Assignment%202/reports/Assignment-2-Convolutional-Neural-Networks--Vmlldzo1NjQ0NDQ?accessToken=y98grmei3a3l8mz4mlfv008r091zssbrwvqlu693mzjz6o9yw79ogbez3t5xabz4)

Part A:
  1) Train a CNN from scratch: Our model has 5 sets of Conv and MaxPooling layers followed by a dense layer and an output layer. We have also implemeted 4 types of Data Augmentations, viz. Random Flip, Random Crop, Random Rotation and Random Tranlation. Batch Normalization, Dropout and change in filter organization (doubling the no. of filters after each layer, halving the number of filters after each layer or using the same number of filters after each layer, are also being implemented, so that the models which perform the best on the validation dataset is chosen for further analysis. 
  2) Sweep and perform hyperparameter tuning: We have performed hyperparameter tuning with a host of hyperparameters: maximum no. of epochs(max_epoch), initial number of filters (num_filters), filter organization, which takes care of doubling, halving or having the same number of filters after each layer (filter_org), whether to implement data augmentation or not (data_augmentation), dropout to be used (dropout), whether batch normalization is to be used or not (batch_normalization) and the optimizer to be used (optimizer)
  3) Visualize filters in 1st layer
  4) Perform Guided Backpropagation
      a) Selecting random neuron in the CONV5 Layer and make all other outputs zero. \\
      b) Removing negative gradients during backpropagation using a GuidedRelu function.

Part B:
  1) Use a pre-existing CNN model
  2) Sweep and perform hyperparameter tuning

Part C:
  1) Make a video with object detection feature using YOLOv3(pre-trained model) - [Reference Model](https://github.com/AlexeyAB/darknet)

### NOTE: Since there was a renaming mistake in one of the files(Part A), please check the commits of the entire folder to have a clear idea of commits and NOT check commits of just the new file. Thank you
