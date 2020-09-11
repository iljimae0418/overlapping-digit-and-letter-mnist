# Extended MNIST Competition 
[Competition Link (hosted by dacon.io)](https://dacon.io/competitions/official/235626/overview/) 

### Notebook Results 
- [mnist no letter.ipynb](https://github.com/iljimae0418/overlapping-digit-and-letter-mnist/blob/master/mnist_no_letter.ipynb) - 93.6% public leaderboard score, grade 7 model and augmentation level 2 but without using any letter information. 
- [grade_5_model_training.ipynb](https://github.com/iljimae0418/overlapping-digit-and-letter-mnist/blob/master/grade_5_model_training.ipynb) - 90.2% public leaderboard score, grade 5 model modified to batch normalize input before passing it into convolution layer. Augmentation level 3 
- [with standardization.ipynb](https://github.com/iljimae0418/overlapping-digit-and-letter-mnist/blob/master/with%20standardization.ipynb) - 91.2% public leaderboard score using sklearn.utilities shuffle(), standardization of input, grade 5 model, augmentation level 2, 10-fold cv   
- [mnist_cnn_kfold_experiment.ipynb](https://github.com/iljimae0418/overlapping-digit-and-letter-mnist/blob/master/mnist_cnn_kfold_experiment.ipynb) - 90.2% public leaderboard score for custom k-fold without shuffling, 87.7% public leaderboard score for sklearn KFold with shuffling. Both using grade 4 model and min-max scaling of input, augmentation level 1, 5-fold cv for both. 

### References 
- [Don't use dropouts in CNNs](https://www.kdnuggets.com/2018/09/dropout-convolutional-networks.html) 
- [Elastic Distortions](https://www.kaggle.com/babbler/mnist-data-augmentation-with-elastic-distortion)
- [Inception (GoogLeNet) Review](https://kangbk0120.github.io/articles/2018-01/inception-googlenet-review)
- [PReLU activation](https://medium.com/@shoray.goel/prelu-activation-e294bb21fefa)
