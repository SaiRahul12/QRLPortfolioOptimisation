# Quantum Reinforcement Learning for Enhanced Portfolio Optimization

This project implements quantum algorithms for financial portfolio optimization, aiming to reduce errors and improve accuracy in computing expected returns from assets. The project explores the use of quantum algorithms, specifically the Quantum Approximate Optimization Algorithm (QAOA) with Conditional Value-at-Risk (CVaR) adaptation, for solving the combinatorial optimization problem of portfolio optimization.

## Project Overview

The goal of this project is to implement quantum algorithms for optimizing financial portfolios. It addresses the combinatorial optimization problem of selecting the best combination of assets (commodities, bonds, securities, etc.) from a finite set of solutions to maximize returns, minimize risk, and stay within a specified budget.

The project compares the performance of quantum reinforcement learning (QAOA with CVaR adaptation) with classical machine learning (LSTM) and non-machine learning (GRG Nonlinear) approaches for portfolio optimization.

## Implementation Methodology

1. **Non-Machine Learning**: Excel's GRG (Generalized Reduced Gradient) Nonlinear Solver/Optimizer.
2. **Classical Machine Learning**: Long Short-Term Memory (LSTM) neural network with Principal Component Analysis (PCA) and SciPy optimizer for portfolio optimization based on the Sharpe ratio.
3. **Quantum Reinforcement Learning**: QAOA (Quantum Approximate Optimization Algorithm) with CVaR (Conditional Value-at-Risk) adaptation using the Qiskit SDK.

## Dataset

The project uses a portfolio dataset of 5 assets from the US Stock Exchange, generated using Yahoo Finance historical trading data (2015-2020) for the following stocks:

- IBM (IT Industry)
- Pfizer (Healthcare/Pharmacy)
- Exxon Mobil Corp. (Oil & Gas)
- Bank of America (Finance/Banking)
- Tesla (Automobile/Technology)

## Results

The project compares the performance of the three approaches (non-machine learning, classical machine learning, and quantum reinforcement learning) in terms of portfolio optimization metrics such as expected return, variance, standard deviation, and Sharpe ratio.

## Getting Started

To run this project, you'll need to have Python 3.x (>= 3.7) installed, along with the following dependencies:

- Qiskit (for quantum reinforcement learning)
- Keras (for classical machine learning)
- Pandas, NumPy, Yahoo Finance, Scikit-learn, SciPy (for data handling and classical machine learning)

Additionally, you'll need access to a quantum computing simulator or a quantum computer (if available) to run the quantum algorithms.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Quantum Approximate Optimization Algorithm (QAOA)](https://arxiv.org/abs/1411.4028)
- [Improving Variational Quantum Optimization using CVaR](https://arxiv.org/abs/1907.04769)
- [Qiskit Textbook](https://qiskit.org/textbook/preface.html)
