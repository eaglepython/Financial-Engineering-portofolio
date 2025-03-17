Portfolio Overview
A financial engineer and data scientist with expertise in quantitative finance, machine learning, and risk modeling. This portfolio presents key projects in derivative pricing, econometric modeling, portfolio optimization, and financial risk assessment, applying Python, Monte Carlo simulations, Black-Scholes modeling, VaR, and AI-driven forecasting.

Featured Projects
1. Derivative Pricing & Risk Sensitivities
Tools & Techniques: Black-Scholes Model, Monte Carlo Simulations, Binomial Trees, Greeks, Vega, Delta Hedging
 📌 Objective: To price European and American options using multiple valuation techniques and analyze their sensitivities to underlying market conditions.
🔹 Black-Scholes vs. Monte Carlo Methods
Implemented Black-Scholes model to price European call and put options.
Ran Monte Carlo simulations (20,000 iterations) to compare option prices and validate pricing accuracy.
Result: Monte Carlo estimates were within 1.5% deviation from Black-Scholes, confirming model reliability.
🔹 Greeks Sensitivity Analysis
Computed Delta, Gamma, Theta, Vega using numerical differentiation.
Observed that Delta-hedging a call option required a portfolio adjustment of 0.574 shares per contract.
Found Vega impact on option pricing at 19.64 per 1% volatility change.
🔹 American Options: Binomial Tree Pricing
Built binomial models (N=1000 steps) to price American call/put options.
Identified that American puts are always worth more than European puts due to early exercise benefits.
Used early exercise decision rules to compare theoretical and real-world option pricing.
📈 Impact: Enabled accurate pricing of equity derivatives, ensuring risk-aware investment strategies.
📄 Project Report (Full technical details & results)

2. Financial Econometrics: Time Series Analysis & Cointegration Modeling
Tools & Techniques: ADF Test, Johansen Cointegration, VECM, ARIMA, GARCH, Python (statsmodels, NumPy, pandas)
 📌 Objective: To analyze market stability using non-stationary financial time series and develop forecasting models.
🔹 Market Cointegration Analysis (Stock-Index Relationship)
Used Johansen Test to analyze the long-term equilibrium between Apple Stock and NASDAQ Index.
Confirmed presence of one cointegrating vector, validating that Apple stock moves in statistical harmony with the index.
🔹 Vector Error Correction Model (VECM) Implementation
Designed a VECM model to predict Apple’s price movements based on NASDAQ deviations.
Measured speed of adjustment (α coefficient) = -0.14, meaning Apple stock corrects 14% of its deviation per day.
🔹 Risk Forecasting: ARIMA & GARCH Volatility Models
Built ARIMA(1,1,1) model to forecast Apple stock prices.
Used GARCH(1,1) model to quantify conditional volatility and identify high-risk periods.
📈 Impact: Provided quantitative insights for algorithmic trading strategies and risk-adjusted portfolio decisions.
📄 Project Report (Full methodology & implementation)

3. Credit Risk & Collateral Valuation in Fixed Income Securities
Tools & Techniques: Credit Risk Modeling, VaR (Value at Risk), Bond Pricing, Monte Carlo Simulations
 📌 Objective: Assess financing risks in lending and collateral-backed securities.
🔹 Scenario-Based Risk Analysis
Modeled six lending scenarios (secured/unsecured loans, bonds, equity, illiquid securities) and assessed financing vs. collateral risks.
Applied statistical modeling to measure correlations between default rates and economic downturns.
🔹 Fixed Income Market Risk Analysis
Analyzed impact of interest rate fluctuations on bond pricing.
Found that public bond investments had a 22% exposure to interest rate volatility, requiring hedging strategies.
🔹 Value-at-Risk (VaR) & Stress Testing
Implemented Monte Carlo simulations (10,000 paths) to estimate 95% confidence interval for VaR.
Identified worst-case losses across different asset classes.
📈 Impact: Provided credit risk insights to optimize lending policies and enhance capital allocation strategies.
📄 Project Report (Methodology & risk modeling framework)

4. Portfolio Optimization & Algorithmic Trading Strategies
Tools & Techniques: Mean-Variance Optimization, Monte Carlo Portfolio Simulation, Sharpe Ratio, Python (cvxpy, pandas, NumPy)
 📌 Objective: To construct an optimal risk-return portfolio and develop a systematic trading strategy.
🔹 Portfolio Allocation Optimization
Constructed a mean-variance optimized portfolio with highest Sharpe Ratio (1.78).
Allocated 40% equities, 30% bonds, 20% commodities, and 10% cash equivalents based on backtesting.
🔹 Algorithmic Trading Model
Developed a statistical arbitrage strategy using cointegration pairs trading.
Achieved 7% outperformance over traditional buy-and-hold strategies.
📈 Impact: Designed a data-driven investment strategy to maximize returns while managing risk exposure.
📄 Project Report (Trading strategy framework & performance evaluation)

Key Skills Demonstrated
✔ Financial Modeling & Risk Analysis:
Derivative pricing (Black-Scholes, Monte Carlo, Binomial Trees)
Fixed income valuation & bond pricing
Credit risk modeling & collateral risk assessment
✔ Quantitative Trading & Portfolio Optimization:
Mean-variance optimization (Markowitz model)
Algorithmic trading (statistical arbitrage, pairs trading)
Value-at-Risk (VaR) modeling
✔ Machine Learning & AI for Finance:
Time series forecasting (ARIMA, GARCH)
AI-based financial predictions
Cointegration analysis (VECM)
✔ Technical & Programming Expertise:
Python: NumPy, pandas, statsmodels, scikit-learn
Big Data: Hadoop, Spark
Cloud Computing: AWS, Google Cloud
Databases: SQL, PostgreSQL

Conclusion & Career Aspiration
This portfolio reflects my expertise in quantitative finance, machine learning, and financial modeling. My goal is to apply these skills in a financial engineering or risk analytics role contributing to data-driven decision-making and risk mitigation strategies.
