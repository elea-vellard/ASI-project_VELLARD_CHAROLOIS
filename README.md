# MC Dropout - Reproduction of Gal & Ghahramani (2016)

## Overview

This repository contains a Python implementation of the experiments described in the paper "Dropout as a Bayesian Approximation: Representing Model Uncertainty in Deep Learning" by Yarin Gal and Zoubin Ghahramani (ICML, 2016).

The code demonstrates the use of Monte Carlo (MC) Dropout for estimating predictive uncertainty in different tasks including regression, classification and reinforcement learning.
## Contents

* `mc_dropout_reproduction_CHAROLOIS_VELLARD.ipynb`: A Jupyter notebook that reproduces and visualizes the experiments.
* `co2_mm_mlo.csv`: the dataset for the second experiment (model uncertainty in regression tasks) that must be included in the same folder as the notebook.

## Running the Experiments

Open `mc_dropout_reproduction.ipynb` in Jupyter Notebook or JupyterLab and execute the cells sequentially. Our results are already saved in the file, but can be re-run if needed.

## References

Gal, Y., & Ghahramani, Z. (2016). [Dropout as a Bayesian Approximation: Representing Model Uncertainty in Deep Learning](http://proceedings.mlr.press/v48/gal16.pdf). ICML.
