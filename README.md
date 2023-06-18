# M-SafeUCB
Accompanying code for the paper "Benefits of Monotonicity in Safe Exploration with Gaussian Processes" (UAI 2023)


- To run the code, please use the modified version of the Trieste toolbox for Bayesian Optimisation provided here.

- Changes:
  - MSafeUCB algorithm added
  - SafeOpt algorithm added
  - PredVar algorithm added
  - Objective functions used in the paper added
  - Function to plot safe boundary added

- To run the inverted pendulum experiment, please install OpenAI Gym and replace the pendulum.py file with the one provided here. This file contains added functionality to modify the initial state of the pendulum as per the specifications in the paper, as well as the modified reward function.

- Relevant Python notebooks:
  - MSafeUCB_Trieste/docs/notebooks/Safe_BO_Synthetic_Data.ipynb
  - MSafeUCB_Trieste/docs/notebooks/Safe_BO_Inverted_Pendulum.ipynb
