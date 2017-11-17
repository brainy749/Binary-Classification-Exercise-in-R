# Binary-Classification-Prediction

In this binary classification problem, the objective is to build a classifier only with the training data, with the goal of achieving the best performance possible on the validation data.

We start by considering the following models GLM (Elastic Net with logistic function and regularisation), Gradient - Boosting Machines (gbm), XGboost, Random Forest, multilayer artificial neural network in H2o and then select a lead model with H2o AutoML algorithm. 

In this exercise, the best performance model was a gbm (with 81 trees and max depth of 8)  giving  `AUC of 0.767259571902321` on on the validation data.

Contents: 

- R Markdown file (`pmaddo_kreditech_exercise.Rmd`) 
- Html Output from Rmd file (`pmaddo_kreditech_exercise.html`). 
- You can easily read through the html output like a report by selecting **Show All code** at the top right corner of the html to display R codes and comments :) 
- See `Section 3.7.3` for details on the gbm model. 
