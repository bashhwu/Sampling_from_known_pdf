# Sampling_from_known_pdf

The aim of this repo is to show how to sample from a distribution with known pdf. 
This can be performed using one of the folowing methods: 

1-Inverse CDF
2-Slice sampler
3-MCMC (Markov Chain Monte Carlo): Hasting-Mteropolis sampling
4-HMC: Hamiltonian (Hybrid) Monte Carlo

The distribution addressed in this repo is the Exponentially modified Gaussian Distribution. 

These methods suffer from high computational cose when it comes to generate samples for a large batch size. 
