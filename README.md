# Markowitz Portfolio Optimization with Frank-Wolfe and Projected Gradient Methods

## Introduction

In the landscape of financial investments, the construction of an optimized portfolio is paramount. This project takes inspiration from the Markowitz's Modern Portfolio Theory (MPT), a theory that suggests how rational investors can use diversification to optimize their portfolios.

Our endeavor is to apply various optimization techniques, namely the Frank-Wolfe method, Pairwise Frank-Wolfe, and Projected Gradient method, to optimize the portfolio's loss function under specific constraints. These techniques aim to find the optimal set of asset weights that minimizes the portfolio's risk for a given level of expected return.

## Optimization Methods

### 1. Frank-Wolfe Method

The Frank-Wolfe method, also known as the conditional gradient method, is an iterative algorithm used for optimizing smooth functions over compact sets. In the context of this project, it will be utilized to find the optimal weights for assets in a portfolio.

### 2. Pairwise Frank-Wolfe

A variant of the traditional Frank-Wolfe method, the pairwise method leverages the optimization procedure by considering pairs of assets in each iteration, potentially offering a more refined solution.

### 3. Projected Gradient Method

The Projected Gradient method is an optimization technique that combines the gradient descent method with a projection step that ensures the solution remains in the feasible set in each iteration. This method is particularly suited for problems with convex objective functions and convex constraints.

## Loss Function and Constraints

The loss function is based on the Markowitz’s portfolio theory, which considers the expected returns of the assets, as well as the covariance between the asset returns, to find the portfolio with the minimum risk. The constraints ensure the validity of the portfolio, including constraints on the asset weights such that they sum up to one and are non-negative.

### Loss Function

\[
\text{Minimize: } Q(w) = w^T \Sigma w - \lambda r^T w
\]

where:
- \(Q(w)\): Loss function
- \(w\): Vector of asset weights in the portfolio
- \(\Sigma\): Covariance matrix of asset returns
- \(r\): Vector of expected asset returns
- \(\lambda\): Risk aversion coefficient

### Constraints

The optimization problem is subject to the following constraints:

1. **Weight Summation Constraint**: The sum of the weights of all assets in the portfolio should be equal to one. This is mathematically represented as:
   
   \[
   \sum_{i=1}^n w_i = 1
   \]

2. **Non-negativity Constraint**: The weights should be non-negative to avoid short selling. This is mathematically represented as:

   \[
   w_i \geq 0, \text{ for all } i
   \]

3. **Cardinality Constraint (optional)**: In some cases, we might want to limit the number of assets in the portfolio to a fixed number \(k\). This is mathematically represented as:

   \[
   \sum_{i=1}^n I(w_i > 0) \leq k
   \]

where \(I(\cdot)\) is the indicator function.

Feel free to adjust the objective function and constraints as per your specific requirements and the details of your project.


