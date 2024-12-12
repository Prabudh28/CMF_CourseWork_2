Project Overview

Abstract

The project provides a comprehensive analysis of computational methods for option pricing and volatility estimation. Key areas of focus include:

Option Pricing:

Evaluation of European call options using the Black-Scholes-Merton (BSM) model and Monte Carlo simulation.

Validation of results and performance comparison.

Implied Volatility:

Comparison of historical and implied volatilities.

Estimation of implied volatility using the Newton-Raphson method.

Application to Tesla’s put options and comparison with historical volatility.

Binomial Tree Option Pricing:

Implementation of a three-step binomial tree for American call options.

Python implementation and manual calculations with result comparisons.

File Descriptions

1. Documentation

CMF_Coursework2.docx: Detailed report including the theoretical background, methodology, Python implementation, and results.

2. Code

CMF_Coursework_2.ipynb: Jupyter Notebook containing Python code for:

Black-Scholes-Merton option pricing.

Monte Carlo simulation for option pricing.

Newton-Raphson method for implied volatility estimation.

Binomial tree option pricing for American options.

Key Results

Option Pricing:

BSM Price: $8.02

Monte Carlo Price: $8.04

Both methods provided consistent results, demonstrating the validity of the implementation.

Implied Volatility:

Implied volatility was estimated for Tesla’s put options with strike prices of $140 and $340.

Comparison with historical volatility provided insights into market expectations.

Binomial Tree Pricing:

American call option price (t=0): $11.01 (manual calculation), $11.04 (Python implementation).

Prerequisites

To run the Jupyter Notebook, ensure the following dependencies are installed:

Python 3.8+

Jupyter Notebook

Libraries: numpy, scipy, matplotlib, yfinance

You can install the required libraries using:

pip install numpy scipy matplotlib yfinance

Usage

Clone the repository:

git clone <repository-url>

Navigate to the directory:

cd CMF_Coursework2

Open the Jupyter Notebook:

jupyter notebook CMF_Coursework_2.ipynb

Run the cells sequentially to reproduce the results.

Repository Structure

.
├── CMF_Coursework2.docx       # Detailed report
├── CMF_Coursework_2.ipynb     # Jupyter Notebook
├── README.md                  # This file

References

Black, F. and Scholes, M. (1973). The pricing of options and corporate liabilities. Journal of Political Economy.

Boyle, P. P. (1977). Options: A Monte Carlo Approach. Journal of Financial Economics.

Hull, J. C. (2021). Options, Futures, and Other Derivatives. Pearson.

Cox, J. C., Ross, S. A., & Rubinstein, M. (1979). Option Pricing: A Simplified Approach. Journal of Financial Economics.
