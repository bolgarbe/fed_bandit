# Variational inference for federated bandits

Toy implementation of a variational bayesian inference method for federated multi-armed bandits. The detailed description can be found in the lecture notes. Briefly, this model differs from traditional federated approaches (e.g. FedAvg) by explictly modeling uncertainty, which, in a sense, drives the aggregation of model parameters.