# Bayesian-Inference

## Background

Gaussian process regression (GPR) is a nonparametric, Bayesian approach to regression, which has received increased attention in the machine-learning community over the past decade, and it can be seen that GPR model is widely used in many different studies.  

## Data

This is a case study using Gaussian regression, with data from a H2 dissociation curve with energies E calculated at FCI/aug-cc-pV6Z for 451 different internuclear distances R. The E data is in `E_FCI_451.dat` and the R data is in `R_451.dat`.   

## Implementation

In the case studying, We have drawn a uniform sampling subsample with a sample size of 17 from the original data.  Since the essential part of GPR is the selection of the kernel function, we consider several different kernel functions to make inference, such as the RBF kernal, the Martern 3/2 kernal and so on. The code file `Bayesian-inference.ipynb` contains detailed background knowledge of Gaussian process regression and shows the prior distribution of these kernel functions and their posterior distribution under E-R data.
