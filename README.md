# Volatility-Models

## Two-Factor Bergomi Model

Implementation of the **Two-Factor Bergomi stochastic volatility model** for pricing equity and volatility derivatives using Monte Carlo simulation.

### Overview

This project implements the numerical methods required to:

- Simulate asset price paths under the Two-Factor Bergomi model
- Validate the model's correlation structure
- Price **SPX options**
- Price **VIX futures**
- Price **VIX options**
- Compute implied volatilities from simulated option prices

The notebook follows the computational assignment for NYU's **Volatility Models (FRE-GY 6901)** course.

### Methods

- Exact simulation of Ornstein-Uhlenbeck volatility factors
- Monte Carlo simulation
- Cholesky decomposition for correlated Brownian motions
- Black-Scholes implied volatility inversion

## Particle Method for Smile Calibration

Implementation of the **Particle Method** for calibrating a **Stochastic Local Volatility (SLV)** model using Monte Carlo simulation and kernel regression.

### Overview

The notebook includes:

- Monte Carlo simulation of the SLV model
- Particle-based estimation of the leverage function
- Quartic kernel regression for conditional expectation estimation
- Black-Scholes option pricing and implied volatility calculations
- Volatility smile calibration and visualization

### Methods

- Particle Method
- Kernel Regression (Quartic Kernel)
- Monte Carlo Simulation
- Stochastic Local Volatility Modeling
- Black-Scholes Pricing & Implied Volatility
- SciPy
- Matplotlib
