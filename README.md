# Reinforcement Learning Assignment 2

## Table of Contents
- [Contributors](#contributors)
- [Overview](#overview)
- [Environments and Algorithms Implemented](#environments-and-algorithms-implemented)
- [Parameter Tuning](#parameter-tuning)
- [Results](#results)
- [Setup and Reproduction Guide](#setup-and-reproduction-guide)
- [Contact](#contact)

## Contributors
- **Chowdhury Nafis Saleh**
  - ID: 202381888
- **Md Jawad Khan**
  - ID: 202381977

## Overview
This repository contains our work on various gridworld problems, exploring different reinforcement learning algorithms and environmental setups. The assignment's objective was to implement and analyze these algorithms' performance in different scenarios, including non-stationary environments.

## Environments and Algorithms Implemented
We have implemented and analyzed the following:

1. Basic Gridworld:
   - Value function estimation using Bellman equations
   - Iterative policy evaluation
   - Value iteration

2. Gridworld with Monte Carlo methods:
   - Monte Carlo with exploring starts
   - Monte Carlo with ε-soft policy

3. Gridworld with Permuting Squares:
   - Value iteration in a non-stationary environment

## Parameter Tuning
We conducted parameter tuning for the following elements:
- Discount factor (γ)
- Epsilon value for ε-soft policies
- Number of episodes for Monte Carlo methods
- Convergence thresholds for iterative methods

## Results
Our findings are detailed in the Jupyter Notebook (and also in the pdf submitted through email), with plots illustrating:
- Value function heatmaps
- Optimal policy visualizations
- Comparisons between different methods and environmental setups

## Setup and Reproduction Guide

### (Recommended Process) 
The `.ipynb` file can be executed by uploading it to Google Colab.

### Alternative Local Setup

#### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: `numpy`, `matplotlib`, `seaborn`

#### Installation
1. Clone the repository:
   ```
   git clone [repository-link]
   ```
2. Install the required libraries:
   ```
   pip install numpy matplotlib seaborn
   ```

#### Execution
1. Navigate to the repository's directory:
   ```
   cd [repository-name]
   ```
2. Start Jupyter Lab:
   ```
   jupyter lab
   ```
3. Open the `RL_Assignment2.ipynb` file and execute the cells to see the code and results.

### Results Analysis
The embedded plots and discussions within the notebook will guide you through our analysis. Key areas to focus on include:
- Comparison of value functions across different methods
- Analysis of optimal policies in various gridworld setups
- Impact of the permuting squares on the learned policies
  
**A way more in dept section wise result analysis and discussion is included in the report and the code file**

## Contact
Should you have any questions, please contact us at:
- Chowdhury Nafis Saleh - cnafissaleh@mun.ca
- Md Jawad Khan - mjawadk@mun.ca
```
