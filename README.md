# Portfolio Optimisation and Financial Modelling Capstone

This project implements a series of financial modelling and portfolio optimisation exercises using historical market data. The objective is to apply core quantitative finance concepts such as return calculations, portfolio variance, the efficient frontier, and risk-adjusted performance to construct and evaluate investment portfolios.

The project was completed as part of the **Wharton Business and Financial Modeling Capstone** and uses Excel to perform statistical analysis, optimisation, and portfolio construction.

---

# Project Overview

The project progresses through five stages:

1. Data preparation and return calculation  
2. Statistical analysis of asset returns  
3. Portfolio optimisation using mean–variance theory  
4. CAPM analysis  
5. Multi asset portfolio construction and performance evaluation  

The analysis uses historical price data for ten equities and the **Dow Jones Industrial Average (DJI)**, along with bond and equity index funds.

---

# Data

Historical market data was used for the following securities:

AAPL, MSFT, WFC, DIS, COP, XOM, GOOG, BIDU, TSLA, TTM

Benchmark index:

**Dow Jones Industrial Average (DJI)**

Additional funds used in the diversification exercise:

- VBTLX - Vanguard Total Bond Market Index Fund  
- VFIAX - Vanguard 500 Index Fund  

Daily data spans **June 2010 - June 2016**, with additional monthly data used for portfolio evaluation.

---

# Step 1: Data Preparation

Historical price datasets were imported and organised in Excel.

The dataset includes:

- Daily close prices  
- Adjusted close prices (accounting for dividends and stock splits)  

This data was used to compute daily returns for each security.

---

# Step 2: Return Calculation and Summary Statistics

Daily returns were calculated using both close prices and adjusted close prices.

Return series were then analysed to compute key statistical metrics:

- Mean return  
- Standard deviation (volatility)  
- Minimum and maximum returns  
- Sharpe ratio (risk-adjusted performance)  

This stage highlights differences between individual securities and the broader market index (DJI).

---

# Step 3: Portfolio Optimisation

Modern Portfolio Theory was applied to construct portfolios that optimise the risk–return trade-off.

## Two-Asset Portfolio

An efficient frontier was generated using **MSFT and WFC** by calculating portfolio return and standard deviation across weight combinations.

The **minimum variance portfolio** was identified using both:

- Incremental weight testing  
- Excel Solver optimisation  

The **optimal risky portfolio (tangent portfolio)** was then determined by maximising the Sharpe Ratio.

## Ten-Asset Portfolio

The analysis was extended to include all ten equities.

Portfolio optimisation was performed using:

- Expected returns  
- Covariance matrix of asset returns  
- Mean-variance optimisation  

Two cases were analysed:

- **Unconstrained portfolio (short selling allowed)**  
- **Long-only portfolio (no short selling)**  

Excel Solver was used to maximise the Sharpe ratio subject to portfolio weight constraints.

---

# Step 4: CAPM Analysis

The Capital Asset Pricing Model was applied to estimate:

- **Beta** - sensitivity of each stock to market movements  
- **Alpha** - excess return relative to market expectations  

This was implemented using linear regression of stock returns against DJI returns.

The analysis identifies which securities carry the highest systematic risk.

---

# Step 5: Multi-Asset Portfolio Construction

A final portfolio was constructed using two asset classes:

- **Equities (VFIAX - S&P 500 index fund)**  
- **Fixed income (VBTLX - bond index fund)**  

Using historical monthly returns, the optimal risky portfolio was determined by maximising the Sharpe Ratio.

Optimal allocation:

- **VBTLX:** 67.85%  
- **VFIAX:** 32.15%  

This corresponds to a **$5 million portfolio allocation**.

---

# Portfolio Performance Analysis

The portfolio’s monthly performance (**Jan 2016 - Jul 2016**) was compared against the single stock **AAPL**.

### Key Findings

- AAPL generated higher average returns but significantly higher volatility  
- The diversified portfolio produced smoother returns  
- The diversified portfolio achieved **higher risk-adjusted performance**, as reflected by a higher Sharpe Ratio  

This demonstrates the core principle of **portfolio diversification**: combining assets can reduce overall portfolio risk while maintaining competitive returns.

---

# Key Financial Concepts Applied

- Return calculation  
- Volatility and risk measurement  
- Sharpe Ratio  
- Covariance and correlation  
- Mean-variance optimisation  
- Efficient frontier  
- Tangent portfolio  
- CAPM (Alpha and Beta)  
- Portfolio diversification  

---

# Tools Used

- Excel  
- Excel Solver (portfolio optimisation)  
- Regression analysis (CAPM)  
- Financial modelling techniques  

---
