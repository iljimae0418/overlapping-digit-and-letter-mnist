# overlapping-digit-and-letter-mnist

### Notebook Results 

- [with standardization.ipynb](https://github.com/iljimae0418/overlapping-digit-and-letter-mnist/blob/master/with%20standardization.ipynb) - 91.2% public leaderboard score using sklearn.utilities shuffle(), standardization of input, grade 5 model, augmentation level 2, 10-fold cv   
- [mnist_cnn_kfold_experiment.ipynb](https://github.com/iljimae0418/overlapping-digit-and-letter-mnist/blob/master/mnist_cnn_kfold_experiment.ipynb) - 90.2% public leaderboard score for custom k-fold without shuffling, 87.7% public leaderboard score for sklearn KFold with shuffling. Both using grade 4 model and min-max scaling of input, augmentation level 1, 5-fold cv for both. 
- [modified_mnist_cnn_multiple_filters_experiment.ipynb](https://github.com/iljimae0418/overlapping-digit-and-letter-mnist/blob/master/modified_mnist_cnn_multiple_filters_experiment.ipynb) - public leader score 83.0%. Tried using grade 4 for the first time, min-max scaling of input, 5-fold cv. 
