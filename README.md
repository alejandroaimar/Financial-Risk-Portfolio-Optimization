# Financial Risk Portfolio Optimization

## Overview

This project develops and analyzes a minimum variance portfolio composed of five companies listed on the Mexican Stock Exchange (BMV): FEMSA, Grupo Bimbo, Grupo Televisa, Grupo Financiero Banorte and Walmart de México.

The analysis applies Modern Portfolio Theory (MPT) proposed by Harry Markowitz to determine an optimal asset allocation that minimizes portfolio risk while maintaining diversification benefits. Additionally, several Value at Risk (VaR) methodologies are implemented to assess potential portfolio losses under different market scenarios.

---

## Objectives

- Construct a minimum variance portfolio.
- Analyze the diversification benefits among Mexican equities.
- Estimate portfolio risk using different Value at Risk methodologies.
- Compare risk estimates obtained through Historical, Parametric and Monte Carlo approaches.
- Evaluate portfolio behavior during a period characterized by post-pandemic market volatility.

---

## Data

Historical adjusted closing prices were obtained using the `yfinance` Python library.

### Assets Included

- FEMSA (Fomento Económico Mexicano)
- BIMBO (Grupo Bimbo)
- TELEVISA (Grupo Televisa)
- BANORTE (Grupo Financiero Banorte)
- WALMEX (Walmart de México)

### Sample Period

January 2021 – January 2023

This period includes relevant economic events such as:

- Post-COVID market recovery
- High inflation environment
- Interest rate increases
- Significant fluctuations in Mexican equity markets

---

## Methodology

### 1. Portfolio Optimization

The portfolio was constructed using Harry Markowitz's Modern Portfolio Theory.

The optimization process seeks the portfolio weights that minimize total portfolio variance while maintaining full investment allocation.

### 2. Historical VaR

Historical VaR estimates potential losses using the empirical distribution of historical returns without assuming a specific probability distribution.

### 3. Parametric VaR

Parametric VaR assumes that portfolio returns follow a normal distribution and estimates risk using the mean and standard deviation of returns.

### 4. Monte Carlo VaR

Monte Carlo simulation generates thousands of potential future return scenarios to estimate the distribution of possible losses.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- SciPy
- Matplotlib
- yfinance

---

## Financial Concepts Applied

- Modern Portfolio Theory (Markowitz)
- Portfolio Diversification
- Portfolio Volatility
- Risk Management
- Historical VaR
- Parametric VaR
- Monte Carlo Simulation

---

## Results

The project provides:

- Optimal portfolio weights
- Portfolio volatility estimates
- Return distribution analysis
- Historical VaR estimates
- Parametric VaR estimates
- Monte Carlo VaR estimates
- Comparative risk assessment

---

## Project Structure

```text
Portfolio-Risk-Analysis-VaR-Python

├── Images
├── Code
├── Notebook
├── Report
└── README.md
```

---

## Author

**Alejandro Aimar y compañeros de la carrera**

Actuarial Science Student | Finance & Risk Management Enthusiast
