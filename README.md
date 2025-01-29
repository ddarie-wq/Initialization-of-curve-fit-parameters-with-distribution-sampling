# Starting Right: Exploring the impact of random distribution sampling on initial Parameter selection for curve fitting

Darie Dan

code used for the thesis *Starting Right: Exploring the impact of random distribution sampling on initial Parameter selection for curve fitting*\
BSc Computer Science and Engineering, TU Delft, 2025

## About
This project explores how sampling the initial parameters' values from random distribution affects process of curve fitting using Levenberg-Marquadt method, by comparing between 2 distributions: normal and uniform and changing the parameters of those 2 distributions.

This is part of the [Research Project 2025](https://github.com/TU-Delft-CSE/Research-Project) of [TU Delft](https://www.tudelft.nl/).

## Experiments done
- Default Uniform(0lower bound,1 upper bound) vs Standard Normal Distribution.
- Negative Uniform(negative lower bound, upper bound) vs Standard Normal Distribution
- Increased bounds uniform distribution vs default uniform distribution
- Increased bounds normal distribution vs standard normal distribution
- Handcrafted sampling initialization for both distributions
### How to run
1. Install `numpy`, `scipy`, `matplotlib`, `h5py`, `sklearn`.
 2. Load the LCDB dataset and export to hdf5.
3. Set the parameters of the functions with regards to the data presented in the paper
4. run all the cells
---

**Dataset**: All learning curves come from the dataset of [LCDB](https://github.com/fmohr/lcdb).
