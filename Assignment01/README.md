Link to the code: https://github.com/kodikarthik21/CS6910---Fundamentals-of-Deep-Learning/blob/main/Assignment01/CS6910_Assignment1.ipynb

Link to the report: https://wandb.ai/karthik21/cs6910-assignment01/reports/CS6910-Assignment-1--Vmlldzo1MDI5MzE

For Questions 1,2,3 and 4, the codes are written separately, with the question put in the text box prior to the code for the question. The plots are present in the report. The
function names are pretty self-explanatory, as the purpose served by the function is given as the function name. Logging on to wandb is necessary to generate and see the plots.

Questions 5 and 6 are based on the plots generated in Question 4 and the intuitions drawn from them. The plots and the intuition derived from the plots are given in the report in 
detail.

The confusion matrix given in Question 7 was generated using wandb only. It is a pretty interactive confusion matrix as it shows the number of examples for each set.

Till now, we had used cross-entropy loss. In Question-8, we used the squared error loss. Even though the accuracies are similar, the values of the loss are drastically different. The plot in the report shows this.

We chose the set of hyperparameters for fashion-MNIST which gave the highest accuracies and used the same on the MNIST dataset. This gave really high accuracies. So, the hyperparameters used for one training set can be very well used for the other training set.

The code is pretty self-explanatory and sequential. Run the cells one after the other to get the desired plots.
