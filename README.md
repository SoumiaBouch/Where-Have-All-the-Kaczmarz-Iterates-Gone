# Where Have All the Kaczmarz Iterates Gone?

This repository is the official implementation of the numerical results presented in The Paper _Where Have All the Kaczmarz Iterates Gone?_ 

## Requirements
We conducted the experiments using python 3.9.2, pandas 1.2.3, numpy 1.20.1, and scipy 1.8.0. The numerical results can be easily reproduced by running the provided Jupyter notebooks available in the repository. The Jupyter notebooks can be run using any editor, such as VS Code, Anaconda, and others.

The real datasets used in the experiments are from [LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/) and are also available in this repository as .csv files.

### Limiting ball of final RK iterates.
To visualize the limiting balls of final RK iterates, please run the nootbooke limitting_balls_2D.ipynb.

### Comparing Bounds for noise-free systems.
To run the experiments comparing the bounds in the noise-free case, please run the notebook comparing_bounds_noiseless.ipynb.

### Comparing Bounds for noisy systems.
To run the experiments comparing the bounds in the noisy case, please run the notebook comparing_bounds_noisy.ipynb.
