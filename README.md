# MonteCarlo-Pi-Estimation
MATLAB project for estimating π using Monte Carlo simulation (AMS 595 Project)

## Project Overview  
This project implements the Monte Carlo method to approximate the value of π.  
The method works by generating random points in the unit square and checking how many fall inside the quarter circle of radius 1. Since the ratio of the areas equals π/4, multiplying the proportion of points inside by 4 gives an estimate of π.  

The project contains three tasks:  
1. **Task 1**: Fixed number of points (for-loop).  
   - Runs simulations for different sample sizes.  
   - Produces plots for:  
     - π estimate vs. N  
     - Absolute error vs. N  
     - Runtime vs. N  

2. **Task 2**: Precision-based stopping criterion (while-loop).  
   - Runs until the estimate stabilizes to a required number of significant figures.  
   - Uses a "streak" parameter M to ensure stability.  

3. **Task 3**: Function with live scatter plotting.  
   - Function: `mc_pi_task3`  
   - Plots points inside the circle (blue) and outside (red).  
   - Updates a live display of the current estimate of π.  

---

## Requirements  
- MATLAB R2021a or later (older versions may also work).  
- No additional toolboxes are required.  
- Figures/plots are generated with MATLAB’s built-in plotting functions.  

---
