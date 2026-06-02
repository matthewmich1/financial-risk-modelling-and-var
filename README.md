### **Project: Quantitative Risk Modelling of Global Equity Markets**

### Overview
Estimated the downside risk of an equally weighted portfolio consisting of the S&P 500 and Nikkei 225. 
Modelled return dynamics and dependence structures to estimate portfolio Value-at-Risk (VaR) and Conditional Value-at-Risk (CVaR) using ARMA-TGARCH models, 
Student-t copulas, and Monte Carlo simulation.

### Key Concepts & Skills Demonstrated
- Financial Time Series Analysis
- ARMA Modelling
- TGARCH Volatility Modelling
- Heavy-Tailed and Skewed Distributions
- Probability Integral Transform (PIT)
- Copula Modelling
- Monte Carlo Simulation
- Value-at-Risk (VaR)
- Conditional Value-at-Risk (CVaR)
- Model Selection and Diagnostic Testing
- Portfolio Risk Management

## Technologies Used
- R
- R Markdown

### Results
Final model combined ARMA-TGARCH marginal distributions with a Student-t copula to generate 10,000 simulated joint return scenarios. These simulations were used to estimate portfolio downside risk through 95% and 99% VaR and CVaR measures.
