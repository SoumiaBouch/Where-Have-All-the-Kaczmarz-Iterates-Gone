# Where Have All the Kaczmarz Iterates Gone?

This repository is the official implementation of the numerical results presented in the paper _Where Have All the Kaczmarz Iterates Gone?_ 

## Requirements
All experiments were conducted using Python 3.9.2 with the following dependencies: pandas 1.2.3, numpy 1.20.1, and scipy 1.8.0. The numerical results can be reproduced by running the Jupyter notebooks available in the repository using any compatible editor such as VS Code or Anaconda.

The real datasets used in the experiments are from [LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/) and are included in this repository as CSV files.

### Comparing Bounds for Noisy Linear Systems
Run the notebook `comparing_bounds_noisy.ipynb` to reproduce experiments that compare the theoretical bounds for the Randomized Kaczmarz algorithm applied to noisy linear systems.

### Comparing Bounds on Real-World Data
Run the notebook `comparing_bounds_real_data.ipynb` to reproduce experiments that compare the bounds for RK applied to real-world data.

### Empirical Validation of Theorem 3.2
Run the notebook `comparing_bounds_real_data.ipynb` to reproduce experiments that evaluate Theorem 3.2

### Limiting Ball of Final RK Iterates
Run the notebook `limiting_balls_2D.ipynb` to generate visualizations of the limiting balls of the final RK iterates.
