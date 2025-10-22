# Bayesian Neural Network Time Series

This project is about how to apply the Bayesian framework with the neural network in time series prediction and explanation. Currently, we are considering weights and biases in the neural network as random variables, assigning a prior and calculating the posterior distributions to provide the uncertainty of the prediction. 

Given a time series, $t_1, t_2, \dots, t_d$, we want to use a single perceptron to predict the next timestamp value $t_{d+1}$. The formula would be $$t_{d+1}=f(\sum_{i=1}^d w_it_i+ w_0)$$ where the $f$ is the non-linear activation function. We want to assign a structure to the prior distribution of weights and biases where $w_d$ has stronger influence than $w_1$.
