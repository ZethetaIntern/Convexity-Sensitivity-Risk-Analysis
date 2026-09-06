# Convexity-Sensitivity-Risk-Analysis
## Project Overview

This project presents an integrated fixed-income portfolio risk analysis solution using Power BI and Python. It focuses on measuring interest-rate sensitivity, duration, convexity, DV01, key-rate risk, yield shocks, and scenario-based portfolio impacts.

The solution combines a Python-based analytical workflow with an interactive Power BI dashboard to support portfolio risk monitoring and visualization.

## Objectives

- Analyze fixed-income portfolio interest-rate risk.
- Measure portfolio Duration, Convexity, and DV01.
- Analyze risk contribution by sector and credit rating.
- Evaluate sensitivity to different yield shocks.
- Analyze key-rate duration across maturity buckets.
- Estimate portfolio P&L and value changes under scenarios.
- Provide interactive dashboards for portfolio risk analysis.

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Power BI
- DAX
- Excel / CSV data

## Project Components

### 1. Python Analysis

`Convexity_Sensitivity_AI_Agent.ipynb`

The Python notebook performs portfolio-level fixed-income risk calculations and generates analytical outputs for use in the dashboard.

Key analysis includes:

- Portfolio market value
- Portfolio weights
- Modified Duration
- Convexity
- DV01
- Risk contribution by credit rating
- Risk contribution by sector
- Yield-shock sensitivity
- Price impact
- Scenario P&L
- Portfolio value sensitivity
- Analytical charts and exported results

### 2. Power BI Dashboard

`Convexity_Sensitivity_Risk_Analysis.pbix`

The Power BI report provides interactive visualization of the fixed-income portfolio risk analysis.

## Dashboard Pages

### Executive Summary
Provides an overall view of portfolio risk metrics and key portfolio indicators.

### Risk Contribution
Analyzes duration, DV01, and convexity contributions across sectors and credit ratings.

### Yield Sensitivity
Shows portfolio sensitivity to different yield shocks and their impact on price, value, and P&L.

### KRD Analysis
Analyzes key-rate risk across maturity buckets and evaluates duration, DV01, and convexity contributions.

### Monte Carlo
Provides scenario-based portfolio risk analysis using simulated scenarios.

### VaR & CVaR
Presents portfolio loss-risk measures using Value at Risk and Conditional Value at Risk analysis.

### ML Model Comparison
Provides the model-comparison section included in the Power BI report.

### Scenario Analysis
Evaluates portfolio behavior under different yield and market scenarios.

## Key Risk Metrics

The project focuses on the following fixed-income risk measures:

- **Modified Duration** — measures sensitivity of bond prices to changes in yield.
- **Convexity** — captures the curvature of the price-yield relationship.
- **DV01** — estimates the portfolio value change for a 1 basis-point yield movement.
- **Key Rate Duration (KRD)** — measures sensitivity to movements at specific maturity points on the yield curve.
- **VaR** — estimates potential portfolio loss at a selected confidence level.
- **CVaR** — measures the expected loss beyond the VaR threshold.
- **Scenario P&L** — evaluates portfolio profit or loss under specified yield shocks.

## Data

The analysis uses fixed-income portfolio data containing information such as:

- Bond identifier
- Issuer
- Sector
- Credit rating
- Currency
- Maturity
- Market value
- Quantity
- Duration
- Convexity
- Spread measures
- Key-rate buckets

## Project Workflow

```text
Portfolio Data
      |
      v
Python Risk Analysis
      |
      +---- Duration
      +---- Convexity
      +---- DV01
      +---- Risk Contributions
      +---- Yield Shock Analysis
      +---- Scenario Analysis
      |
      v
Analytical Outputs
      |
      v
Power BI Data Model
      |
      v
Interactive Risk Dashboard
