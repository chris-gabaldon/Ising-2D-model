Ising Model Monte Carlo Simulations
Overview
This repository contains a Jupyter Notebook for Monte Carlo simulations of the 2D Ising model. The notebook explores the correlation function and susceptibility of the system to estimate the critical temperature.

Notebook Description
The notebook is organized into the following sections:

Correlation Function Calculation: Defines and uses functions to compute the correlation function 
𝑔
(
𝑟
)
g(r) for different temperatures. Results are fitted with an exponential decay to determine the correlation length 
𝜉
ξ.

Susceptibility and Critical Temperature: Calculates susceptibility 
𝜒
χ for various temperatures and estimates the critical temperature 
𝑇
𝑐
T 
c
​
  by fitting the susceptibility peaks with a quadratic function.

Results and Analysis: Plots and analyzes the results to determine the critical temperature and the behavior of the correlation length. Compares the estimated critical temperature with theoretical values.

How to Use
Open the Jupyter Notebook file ising_model_simulation.ipynb in a Jupyter environment.
Run the cells sequentially to execute the Monte Carlo simulations and analyze the results.
Review the generated plots and results for insights into the Ising model's critical behavior.
Results Summary
The critical temperature obtained is 
𝑇
𝑐
=
2.268
±
0.002
T 
c
​
 =2.268±0.002, which is close to the theoretical value 
𝑇
𝑐
=
2.27
T 
c
​
 =2.27.
The notebook also demonstrates how the correlation length 
𝜉
ξ varies with temperature and compares this with the critical temperature.


