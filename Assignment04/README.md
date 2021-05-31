# Assignment 4 - Restricted Boltzmann Machine Training 

### This folder contains the code for Assignment 4 of the course CS6910 - Fundamentals of DL.

### Group members:

Karthik S - ME18B149 Aravint Annamalai - EE18B125

[Gibbs Sampling code](https://colab.research.google.com/drive/1R9a9Wg2gL0BbOhdhaByq58VaQn4sTHgQ?usp=sharing), [Contrastive Divergence Code](https://colab.research.google.com/drive/1V2B4PqygfqqYOnr_dehmNE9-uQYENTPU?usp=sharing)[Report Link(wandb)](https://wandb.ai/kodikarthik21/Assignment-4/reports/Assignment-4--Vmlldzo3MTE4NzU)

The following tasks were performeed as a part of this assignment:
1) Single hidden layer RBM was trained using Gibbs Sampling method and Contrastive divergence method.
2) The hidden layer output of the validation data was used to train a simple logistic regression model which was then checked with test data.
3) Sweeps were performed for hyperparameter tuning of the RBMs.
4) Contrastive Divergence was visualized in 2 ways
    a) The visible layer output was displayed at various steps throughout the epochs
    b) t-SNE visualization

Instructions for running are given in the respective Colab files, which can be accessed using the above links. 

### Note for t-SNE plot
As mentioned in the Contrastive Divergence notebook, the plot will be stored as a file called '''tsne_2d.png'''.
