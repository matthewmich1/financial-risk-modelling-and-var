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
<img width="358" height="86" alt="var-results" src="https://github.com/user-attachments/assets/594e2fe6-9ded-4ffb-aad7-b71b675c7df4" />

Estimated maximum portfolio loss at the 95% and 99% confidence levels based on 10,000 Monte Carlo simulations.

<img width="346" height="90" alt="cvar-results" src="https://github.com/user-attachments/assets/744b524b-ffbe-4e78-ac7e-fdf48b914f1d" />

Estimated average portfolio loss conditional on losses exceeding the corresponding VaR threshold.
