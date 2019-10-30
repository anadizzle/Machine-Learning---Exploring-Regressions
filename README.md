# Exploring Linear and Polynomal Regressions #


This program generates a random data set of to explore the fitting and generalization of regression models via simulation.

X, Y are both real valued random variables, where X takes value in (0, 1) and Y = cos(2*pi*X)+Z where Z is a zero mean Gaussian random variable with variance sigma^2.

This model wil observe a sample of N (X, Y) pairs and kearn a polynomial regression, exampine the fitting and generalization capability of the model in relation to the model complexity and sample size.

 v0.1


### How do I get set up? ###

* Install Anaconda: https://docs.conda.io/projects/conda/en/latest/index.html
* Create new environment: `conda create --name py35 python=3.5`

* Activate the new environment to use it: Linux, MacOS: `conda activate py35`
* Install a new package (Jupyter Notebook) in the active environment
`conda install jupyter`
* Install Numpy: `conda install -c anaconda numpy `
* Install SciKit Learn: `conda install scikit-learn`
* Install Matplotlib`conda install -c conda-forge matplotlib`
* Pytorch set up from Terminal: `conda install python
pytorch torchvision -c pytorch
`
##### Verification of Pytorch set up 
* ```python
from __future__ import print_function
	import torch
	x = torch.rand(5, 3)
	print(x)
```

* Run Jupyter Notebook `jupyter notebook`
* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###