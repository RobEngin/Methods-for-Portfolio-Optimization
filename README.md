### README.md

# Portfolio Optimization Project

## Overview

This project focuses on portfolio optimization using various implementations of the Frank-Wolfe (FW) algorithm within the framework of Markowitz portfolio theory. The algorithms analyzed include:

- **Standard Frank-Wolfe (FW)**
- **Pairwise Frank-Wolfe (PFW)**
- **Away-Step Frank-Wolfe (AFW)**

## Objectives

- **Analyze and compare the performance** of different Frank-Wolfe algorithm variations.
- **Optimize portfolios** for different stock indices: FTSE MIB, EuroStoxx50, and FTSE100.
- **Evaluate algorithms** based on metrics such as loss, risk, return, duality gap, and execution time.

## Project Structure

- **Datasets**: Weekly returns data for FTSE MIB, EuroStoxx50, and FTSE100 from January 22, 2007, to May 6, 2013.
- **Algorithms**: Implementations of FW, PFW, and AFW.
- **Performance Evaluation**: Comparison of algorithms based on key financial metrics.

## Key Components

### 1. Modern Portfolio Theory

- Developed by Harry Markowitz in 1952.
- **Objective**: Maximize expected return for a given level of risk through diversification.

### 2. Algorithms

#### Standard Frank-Wolfe (FW)
- Iterative approach to solve convex programming problems.
- Uses a linear optimization step at each iteration.

#### Pairwise Frank-Wolfe (PFW)
- Improves on FW by selecting two directions at each step to potentially accelerate convergence.

#### Away-Step Frank-Wolfe (AFW)
- Enhances FW by introducing an "away" step, improving convergence when near the boundary of the feasible region.

### 3. Evaluation Metrics

- **Loss Function**: Measures the trade-off between risk and return.
- **Risk and Return**: Calculated for each optimized portfolio.
- **Duality Gap**: Indicates how close the solution is to optimality.
- **Execution Time**: Time taken for each algorithm to converge.

## Results

- **Frank-Wolfe (FW)**: Best performance in loss minimization and duality gap reduction.
- **Away-Step Frank-Wolfe (AFW)**: Fastest in terms of execution time.
- **Pairwise Frank-Wolfe (PFW)**: Best in terms of risk minimization and return optimization.

## Conclusion

The Frank-Wolfe variations provide effective methods for portfolio optimization, each excelling in different aspects. Future work includes adapting these algorithms for more complex financial models and integrating machine learning techniques.

## Authors

- Giovanni Piva
- Roberto Vicentini

---

This project demonstrates the practical application of advanced optimization algorithms in financial portfolio management, providing a comprehensive analysis suitable for academic and professional settings.
