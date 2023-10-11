# Solar-Dyno

Authors:Guillermo Benito-Calviño, Claudia Lorenzetti, Leon Mengoni, Filippo Pra-Floriani

The objective of this project is to conduct Bayesian inference on sunspot data, which
follow the 11-year solar cycle. Given the solar dynamo model, we want to estimate the
best values for the parameters of said model.
In order to test the theory, we first of all construct fake data by simulating the solar
cycle, given fixed values for the parameters of the generative model. Next, we set a prior
and we compute the likelihood. Once we get the expression of the posterior, through a
MAP estimate, we obtain the best values for the parameters. Then, we test the validity
of our setup, by checking if our original parameters reside within the credibility interval
of our MAP parameters.
Subsequently, we conduct inference on the real data.
