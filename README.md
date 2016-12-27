# Bayesian Optimization

Pure Python implementation of bayesian global optimization with gaussian
processes.

    pip install git+https://github.com/fmfn/BayesianOptimization.git

This is a constrained global optimization package built upon bayesian inference
and gaussian process, that attempts to find the maximum value of an unknown
function in as few iterations as possible. This technique is particularly
suited for optimization of high cost functions, situations where the balance
between exploration and exploitation is important.

To get a grip of how this method and package works in the [examples](https://github.com/fmfn/BayesianOptimization/tree/master/examples)
folder you can:
- Checkout this [notebook](https://github.com/fmfn/BayesianOptimization/blob/master/examples/visualization.ipynb)
with a step by step visualization of how this method works.
- Go over this [script](https://github.com/fmfn/BayesianOptimization/blob/master/examples/usage.py)
to become familiar with this packages basic functionalities.
- Explore this [notebook](https://github.com/fmfn/BayesianOptimization/blob/master/examples/exploitation%20vs%20exploration.ipynb)
exemplifying the balance between exploration and exploitation and how to
control it.
- Checkout these scripts ([sklearn](https://github.com/fmfn/BayesianOptimization/blob/master/examples/sklearn_example.py),
[xgboost](https://github.com/fmfn/BayesianOptimization/blob/master/examples/xgboost_example.py))
for examples of how to use this package to tune parameters of ML estimators
using cross validation and bayesian optimization


![BayesianOptimization in action](https://github.com/fmfn/BayesianOptimization/blob/master/examples/bo_example.png)

![BayesianOptimization in action](https://github.com/fmfn/BayesianOptimization/blob/master/examples/bayesian_optimization.gif)


This project is under active development, if you find a bug, or anything that
needs correction, please let me know.

Installation
============

### Installation

BayesianOptimization is not currently available on the PyPi's reporitories,
however you can install it via `pip`:

    pip install git+https://github.com/fmfn/BayesianOptimization.git

If you prefer, you can clone it and run the setup.py file. Use the following
commands to get a copy from Github and install all dependencies:

    git clone https://github.com/fmfn/BayesianOptimization.git
    cd BayesianOptimization
    python setup.py install

### Dependencies
* Numpy
* Scipy
* Scikit-learn

### References:
* http://papers.nips.cc/paper/4522-practical-bayesian-optimization-of-machine-learning-algorithms.pdf
* http://arxiv.org/pdf/1012.2599v1.pdf
* http://www.gaussianprocess.org/gpml/
* https://www.youtube.com/watch?v=vz3D36VXefI&index=10&list=PLE6Wd9FR--EdyJ5lbFl8UuGjecvVw66F6
