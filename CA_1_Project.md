Introduction 

Financial markets operate in a geopolitical environment where diplomatic crises, economic sanctions, and armed conflicts increasingly shape investor sentiment and market volatility. The Dow Jones Industrial Average (DJIA), given its composition of industrial, financial, and energy firms, is particularly exposed to these dynamics.

Traditional volatility models such as GARCH rely almost exclusively on historical price data, treating geopolitical shocks as exogenous noise. However, the growing availability of quantifiable geopolitical risk measures creates an opportunity to test whether external risk factors improve predictive performance. 

The Geopolitical Risk Index (GPR), developed by Caldara and Iacoviello (2022), provides a systematic measure of geopolitical uncertainty, while event-based datasets such as GDELT and ACLED offer complementary information on conflict and geopolitical events. Despite this availability, limited evidence exists on whether such indicators add predictive value when combined with modern machine learning techniques.

This project proposes a machine learning approach to predict DJIA volatility using geopolitical risk indicators. The central research question is: Do geopolitical risk indicators improve the predictive accuracy of machine learning models for DJIA volatility compared to a baseline relying solely on historical price data? Specifically, the project aims to predict realized volatility of the DJIA over a five-day horizon using daily data from 2010 to 2024. 


Problem Definition:

The core problem this project addresses is the limited ability of existing volatility forecasting models to incorporate quantifiable geopolitical risk signals when predicting DJIA volatility. Although geopolitical events are widely recognised as drivers of market uncertainty, their information is rarely integrated directly into traditional forecasting frameworks. Traditional volatility models, including ARCH and GARCH, rely primarily on historical price information and may not fully capture external geopolitical signals.
Failing to address this limitation has direct consequences. Risk managers, portfolio allocators, and financial analysts rely on forecasts that may underestimate volatility during periods of geopolitical tension, leading to suboptimal hedging decisions, inaccurate risk assessments, and unexpected portfolio drawdowns. At the academic level, the gap between quantitative geopolitical research and financial risk modelling remains largely unresolved.
The specific gap addressed by this project is whether incorporating geopolitical risk indicators into machine learning models improves the prediction of DJIA realised volatility compared with models based solely on historical market data.


Add Introduction and Problem Definition
