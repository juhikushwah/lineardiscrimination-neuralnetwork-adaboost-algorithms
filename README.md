DATA- Download the datasets from here: https://archive.ics.uci.edu/ml/machine-learning-databases/optdigits/

Read(for dataset information) - https://archive.ics.uci.edu/ml/datasets/optical+recognition+of+handwritten+digits

-Test set: optdigits.tes

-Training set: optdigits.tra

They have been uploaded in the repository as well.

Purpose:

1. To understand how linear discrimination and neural networks work.

2. To understand AdaBoost algorithm and classifier diversity.

Implemented the logistic regression (i.e. 1 layer neural network with a single sigmoidal output) algorithm in Python using adaptive learning rate and momentum for training(used different learning rate 10 times).

Computed feature importance(as average of absolute value of logistic regression model weight connected to that feature) by eliminating 10%, 25% and 50% of the least important features respectively and trained and tested again to conclude if feature selection was helpful.

Also, used the scikit-learn neural network implementation to train a neural network and test it using the same instances that were used for implementing logistic regression previously. It is a good practice to report the training and testing errors. For this particular implementation, increased the test errors through selection of different number of hidden layers and units as well as weight decay.
This can also be done through selection of different optimization algorithms, feature selection, L1 or L2 regularization, etc.
