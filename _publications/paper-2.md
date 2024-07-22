---
title: "Comparison of group-contribution and machine learning-based property prediction models with uncertainty quantification"
collection: publications
permalink: /publication/paper-2
excerpt: 'In this paper, we benchmark and compare three models and techniques for uncertainty quantification applied to a group-contribution model for the lower flammability limit.'
date: 2021-06-01
venue: 'Computer Aided Chemical Engineering'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/B9780323885065501182'
citation: 'Aouichaoui, A. R., Al, R., Abildskov, J., & Sin, G. (2021). Comparison of group-contribution and machine learning-based property prediction models with uncertainty quantification. In Computer Aided Chemical Engineering (Vol. 50, pp. 755-760). Elsevier.'
---

This study demonstrates the development of three modeling approaches for predicting thermo physical property with the ability to quantify the uncertainty in the prediction. The modeling approaches consist of a classical non-linear group-contribution (GC) model (GCM), Gaussian-Process regression (GPR), and a deep neural network (DNN) all applied to the first-order groups defined by Marrero and Gani as the molecular descriptor. The uncertainty was quantified using different methods: linear error propagation using the parameter covariance matrix for the GCM, the inherent uncertainty quantification of GPR models, and using a probabilistic layer able to learn the distribution of model output sin DNN. The models have been applied to the lower flammability limit (LFL) at 298K. The model performance was evaluated using 5 folds cross-validation to ensure the models were exposed to all data and to detect potential overfitting,—a procedure frequently used with in machine learning. The models obtained produce a good fit to the experimental data when applied to all available data with a coefficient of determination (R2) above 0.9 for all models, a maximum mean absolute error of 0.39 [%-vol], and a maximum mean squared error of 0.51.
