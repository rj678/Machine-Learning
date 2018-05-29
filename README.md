# Machine-Learning

This repo has been set up to understand and use Machine Learning algorithms for various classification and regression tasks. Each task has been set up in a different folder.


## TensorFlow:

### Classification

The folder 'Iris' contains the workflow to train a Neural Network based on the TensorFlow tutorial for the Iris flower classification problem. It also contains a workflow to train an SVM for classification.

Similar workflows will be used for crop classification based on the spectral signals.


### Hyperparameter tuning:

This folder has been set up to better understand the Machine Learning hyperparameter tuning process.


#### Bayesian Optimization

This folder contains a workflow to automate the SVM hyperparameter tuning process of the Iris classification problem with the Bayesian Optimization algorithm, based on the implementation in https://github.com/thuijskens/bayesian-optimization. This is just a first pass - many more iterations will be required to understand and implement this for crop classification (and for tuning Neural Networks).

The notebook should give a general idea of the hyperparameter tuning process. This will be attempted with other global optimization algorithms too.


#### Grid Search

The folder 'challenge' contains files based on a challenge for the reader in the book "TensorFlow for Deep Learning" by Zadeh and Ramsundar, 2018. The challenge is to obtain better validation performance than the Random Forest algorithm for the Tox21 dataset, by using Grid Search to tune the hyperparameters of the Neural Network.

The Tox21 dataset can be loaded by installing the drug discovery machine learning module 'deepchem'. The objective of the Machine Learning task is to predict whether a given compound will be toxic. The dataset was released by NIH and EPA. The dataset that is analyzed consists of a set of 10,000 molecules that are tested for interaction with the androgen receptor. The algorithm seeks to predict whether new molecules will interact with the androgen receptor.

The labels are binary 1/0 for compounds depending on wheteher they interact with the androgen receptor. The Tox21 data set is an imbalanced dataset (far fewer positive sampes than negative samples). The following algorithms have been used:

Fully connected Neural Network with dropout regularization

Support Vector Classifiers



## References

Zadeh, Reza and Ramsundar, Bharath, 2018, TensorFlow for Deep Learning. O'Reilly Media
