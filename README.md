# FiniteNet

Writen by B. Stevens (under T. Colonius)

Code for the FiniteNet paper on [arXiv](https://arxiv.org/abs/2002.03014). 
To run this code, put the `HelperFunctions.py` file into your directory, along with any data you wish to use or trained models you wish to evaluate. 
Then run one of the attached scripts that start with `test` or `train` to test or train a FiniteNet model. 

Requirements:
* numpy
* pytorch
* matplotlib

Datasets:
* Train for inviscid Burgers' equation: https://figshare.com/articles/invBurg_train_npy/11796201
* Train for KS equation: https://figshare.com/articles/ks_train_csv/11796198
* Test for KS equation: https://figshare.com/articles/ks_test_npy/11796186

Linear advection equation was trained and tested with data generated on the fly, as was data for testing inviscid Burgers' equation.
