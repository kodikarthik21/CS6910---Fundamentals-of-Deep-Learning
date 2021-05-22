# Assignment 3 - Sequence to Sequence model for Machine Transliteration

Links: [Wandb Report](https://wandb.ai/kodikarthik21/Assignment-3/reports/Assignment-3-Recurrent-Neural-Networks--Vmlldzo2MzczNjY), [seq2seq_without_attention Colab link](https://colab.research.google.com/drive/1a_Tlb7zOLIna7lk0dbFfWBQIBRPZDsQz?usp=sharing), [seq2seq_with_attention Colab link](https://colab.research.google.com/drive/17YmC8Lyj3ZDgMXzVVtG_4vrCed7mypsg?usp=sharing)

## Preliminaries
Install wandb and store the dataset of your preferred language from [here](https://github.com/google-research-datasets/dakshina) in your Drive with the name lexicons.zip. Run the code under "Attention Class" in [seq_2_seq with attention](https://colab.research.google.com/drive/17YmC8Lyj3ZDgMXzVVtG_4vrCed7mypsg?usp=sharing).

## Dataset preprocessing
Run the cells under the heading of "DATASET PREPROCESSING" to convert the train, validation and test datasets to suitable matrix representations. 

## Building the model and sweep
There is no special isntructions here. Run the model definition function, the function containing the hyperparameters for the sweep and the sweep function (uncomment the line to run the sweep). This calculates the character level and word level accuracies on the validation dataset.

## Test Accuracy and Beam search
Using the best model, the word-level test accuracy using greedy search is computed. Uncomment the lines to do the same. 20 words from the test set is chosen at random and beam search is run on them with beam width = 5. Uncomment the lines in the 'for' loop to do the same.

## Attention Heatmap and Connectivity
10 words from the test set is chosen, and their attention heatmaps and connectivity are generated. Run the cells to reproduce our results.

# NOTE
Even though the code with attention has only one contributor as shown in GitHub, contributions were there from both the team members.
