# Machine-Learning

This repo has been set up to understand and use Machine Learning algorithms for various classification and regression tasks. Each task has been set up in a different folder.


## TensorFlow:

### Hyperparameter tuning:

This folder has been set up to better understand the Machine Learning hyperparameter tuning process.

The folder 'challenge' contains files based on a challenge for the reader in the book "TensorFlow for Deep Learning" by Zadeh and Ramsundar, 2018. The challenge is to obtain better validation performance than the Random Forest algorithm for the Tox21 dataset.

The Tox21 data set can be loaded by installing the drug discovery machine learning module 'deepchem'. The objective of the Machine Learning task is to predict whether a given compound will be toxic. The dataset was released by NIH and EPA. The dataset that is analyzed consists of a set of 10,000 molecules that are tested for interaction with the androgen receptor. The algorithm seeks to predict whether new molecules will interact with the androgen receptor.

The labels are binary 1/0 for compounds depending on wheteher they interact with the androgen receptor. The Tox21 data set is an imbalanced dataset (far fewer positive sampes than negative samples). The following algorithms have been used:

Fully connected Neural Network with dropout regularization

Support Vector Classifiers



## References

Zadeh, Reza and Ramsundar, Bharath, 2018, TensorFlow for Deep Learning. O'Reilly Media
