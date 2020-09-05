The data set I have used is donors choose data set from kaggle.com.

I cleaned the data earlier and compiled it into a pickle file. I have given the google drive link to download the dataset.

Here I have compared the performance score of two decision trees using two different pruning methods.

The first method I have used is commonly called as early stopping criteria or pre-pruning. Here, I used grid search cv form sklearn to find the right combination of hyper parameters.

I have used 2-d and 3-d plots to understand the hyper parameter combinations. I got an AUC score of around 69.5 on testing data.

The second pruning method is cost complexity pruning. As there was only one hyper parameter to be tuned, I used simple for loop to find the best hyper parameter. Although, I have not shown the hyper parameter search process (for loop) in the .ipynb notebook.

The AUC score that I get with the cost complexity pruning is very similar to the previous one. 
