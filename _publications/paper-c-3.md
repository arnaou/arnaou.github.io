---
title: "Molecular representations in deep-learning models for chemical property prediction"
collection: publications
permalink: /publication/paper-c-3
excerpt: 'In this paper we compare three different techniques for modelling the enthalpy of formation: group-contribution, QSPR and graph neural networks.'
date: 2022-06-01
venue: 'Computer Aided Chemical Engineering'
paperurl: 'https://doi.org/10.1016/B978-0-323-85159-6.50265-7'
citation: 'Aouichaoui, A. R., Fan, F., Mansouri, S. S., & Sin, J. A. G. (2022). Molecular representations in deep-learning models for chemical property prediction. In Computer Aided Chemical Engineering (Vol. 49, pp. 1591-1596). Elsevier.'
---

A molecular property prediction model is dependent on the interplay between the quality of data, and expressive representation (or descriptor), and a suitable algorithm to relate the descriptors to the target property. In this work, a deep neural network (DNN) is used to regress two types of descriptors: fixed descriptors (Group fragments and Morgan fingerprints) and learned descriptors (from a Graph Neural Network, GNN). Bayesian optimization was used for hyperparameter tuning and a set of 5 models were benchmarked and used to predict the enthalpy of formation of organic compounds. GNN based models provided the best overall results compared to descriptor-based models which the attentive fingerprint model that combines RNN and graph attention mechanism (AFP) achieved the best results of 5.9 kJ/mol mean absolute deviation and a coefficient of determination of 0.99 in the training, validation, and test set. Despite not achieving chemical accuracy of 4 kJ/mol, the model has shown great promise in distinguishing between isomers and provides a baseline for future improvements to achieve chemical accuracy.
