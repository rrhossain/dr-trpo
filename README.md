## Dristributionally Robust Policy Optimization 

### Tabular: 
* Two algorithms implemented: DRPO KL, DRPO Wasserstein
* This version can run on OpenAI Gym toy text environment, i.e. Taxi-v3, Nchain-v0.
* Policy is not parametrized (i.e. no Neural Network for policies). It's represented as a list that contains PMF of π(·|s) for all states. 

### Classic Control: 
* Three algorithms implemented: DRPO KL, DRPO Wasserstein, A2C (baseline)
* This version can run on OpenAI Gym classic control environment. 
* Policy is parameterized as a neural net that maps from state s to the PMF of π(·|s) 
