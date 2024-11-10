# Portfolio Analysis - Asset Allocation and Performance Evaluation

## Overview

This project was developed as an indivudal quest for the Data Analytics Bootcam from IronHack Berlin, and provides an in-depth analysis of a multi-asset portfolio, examining its historical performance, asset allocation strategy, and risk-return characteristics. The analysis spans from 2019 to 2021 and explores how the portfolio adapted to market conditions, particularly highlighting potential shifts in asset allocation, which may have been influenced by external factors such as the Covid-19 pandemic. The goal is to evaluate the portfolio's resilience, risk-return dynamics, and the strategic decisions behind asset allocation.

Key highlights of this project include:

- **Time Series Analysis**: Analyzing the evolution of portfolio composition and asset weights over time.
- **Asset Allocation Strategy**: Understanding the shifts in asset allocation throughout the period and their potential driving factors.
- **Risk and Return Analysis**: Evaluating the annualized return, volatility, and overall performance of the portfolio.
- **Portfolio Resilience**: Assessing how the portfolio performed during periods of high market volatility and its ability to recover.
- **Asset Return Summary**: Evaluating the performance of individual assets in terms of returns over time, highlighting volatility and growth potential.

## Key Metrics

- **Annualized Return**: 10.336%
- **Annualized Volatility**: 9.93%
- **Average Portfolio Value**: 115.79% of initial value
- **Maximum Portfolio Value**: 134.52% of initial value
- **Minimum Portfolio Value**: 94.42% of initial value

The analysis reveals a generally positive trend in the portfolio’s value over the analysis period, with notable fluctuations, particularly during periods of high market volatility such as the Covid-19 pandemic.

## Asset Performance Summary

The portfolio includes a diverse set of assets with varying levels of risk and return potential. Below is a summary of each asset's individual performance, including both return and volatility:

| Asset    | Mean Return (%) | Min Return (%) | Max Return (%) | Annual Volatility (%) |
|----------|-----------------|----------------|----------------|-----------------------|
| **Asset 1** | 7.53%           | 0.78%          | 11.92%         | 4.78%                 |
| **Asset 2** | 36.07%          | -13.17%        | 87.29%         | 19.02%                |
| **Asset 3** | 22.65%          | -10.72%        | 52.51%         | 18.53%                |
| **Asset 4** | 8.06%           | -9.95%         | 14.12%         | 5.29%                 |
| **Asset 5** | 6.31%           | -26.63%        | 39.61%         | 14.97%                |

### Asset Insights:

- **Asset 1**: A low-risk asset with moderate returns, making it ideal for conservative portfolio strategies. Its low volatility (4.78%) and steady growth (7.53%) position it as a stable performer with lower risk exposure.
  
- **Asset 2**: A high-risk, high-return asset. It showed strong returns (mean: 36.07%), but also substantial volatility (19.02%), reflecting the growth potential typical of sectors such as technology or healthcare. This asset is suitable for investors with a higher risk tolerance.

- **Asset 3**: Similar to Asset 2, but with lower volatility (18.53%) and more moderate returns (mean: 22.65%). It represents a growth-oriented investment, though it is somewhat less volatile than Asset 2.

- **Asset 4**: A stable performer with low volatility (5.29%) and moderate returns (mean: 8.06%). This asset can be a solid choice for maintaining stability while still providing steady returns.

- **Asset 5**: Highly volatile (14.97%) with the potential for large returns (mean: 6.31%). This asset is best suited for high-risk, high-reward strategies, especially considering its sharp recovery after the pandemic shock.

## Strategic Shifts

The analysis reveals potential shifts in asset allocation throughout the period, suggesting a shift toward more stable, lower-risk assets during times of market uncertainty, such as early 2020. In contrast, the portfolio seems to have gravitated toward higher-risk, growth-oriented assets in subsequent years as markets began to recover. These shifts reflect the portfolio’s adaptability and responsiveness to external market conditions, with the goal of optimizing risk-return trade-offs.

## Tools and Libraries Used

- **Python**: The primary programming language for data analysis and visualization.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib** and **Seaborn**: Data visualization for time series analysis and performance charts.
- **NumPy**: Numerical computing for statistical calculations.
- **Scipy**: Statistical tests and correlation analysis.

## Project Structure

This repository contains the following key files and folders:

- **`asset_information_data.csv`**: Asset categories by family (e.g., equity or fixed income).
- **`asset_price_data.csv`**: Raw asset price data (end-of-day prices).
- **`portfolio_weights.csv`**: Portfolio asset weights.
- **`portfolio_analysis.ipynb`**: Jupyter notebook containing the analysis in its entirety.

## Conclusion

This analysis demonstrates how a well-diversified portfolio can adapt to market conditions, recover from downturns, and continue growing despite external disruptions like the COVID-19 pandemic. By strategically adjusting asset allocations, the portfolio maintained a balance between risk and reward, achieving consistent growth over time.

With an annualized return of **10.34%** and an annualized volatility of **9.93%**, the portfolio performed well within the expectations for a balanced risk-return profile. The insights gained from this analysis can help guide future asset allocation decisions and improve portfolio performance.
