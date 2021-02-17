# Generalized Linear Model
To create a GLM model to classify a cell as mutant or wildtype using isoform expression from both long read and short read data.
Here I apply dimension reduction to the dataset before passing the data through the GLM to classify. I use a binomial distribution function since we are predicting an outcome of eitherh 0 or 1 (wildtype or mutant). I use 10-fold cross validation to evaluate my model along with a 60/40 split of the dataset instead of 90/10.
