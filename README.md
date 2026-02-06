# BTC Trading Signal Generation Integrating Market Microstructure and Technical Indicators

### BTC High-Frequency Trading Strategy: Integrating Market Microstructure & Machine Learning

**Project Description:**
Developed a quantitative trading framework utilizing high-frequency market microstructure data and machine learning algorithms to predict short-term Bitcoin price movements and generate trading signals.

* **High-Frequency Data Processing:** Leveraged **Python** to process Binance BTC/USDT 1-minute high-frequency data (including Order Book depth, OHLCV, and Open Interest). [cite_start]Performed rigorous data cleaning and resampling to a 5-minute frequency for analysis[cite: 76, 78, 134].

* [cite_start]**Feature Engineering:** Constructed 18 predictive factors by integrating **Market Microstructure** indicators (e.g., Order Imbalance, Bid-Ask Spread) with technical indicators (RSI, MACD, ATR), effectively capturing short-term price momentum and liquidity shifts[cite: 136, 137, 142].

* **Machine Learning Modeling:** Implemented and evaluated multiple non-linear models including **XGBoost, SVR, Random Forest, and Decision Trees** to predict short-term returns. [cite_start]Utilized **Ridge Regression** for feature selection, demonstrating the significant predictive power of microstructure features over traditional indicators[cite: 276, 274].

* **Strategy Backtesting & Risk Management:** Designed a signal filtering mechanism based on transaction cost thresholds to reduce noise. [cite_start]Implemented an **ATR (Average True Range)** based dynamic framework for adaptive Take-Profit and Stop-Loss execution, ensuring robust risk control[cite: 196, 197].

* [cite_start]**Performance Results:** During periods of extreme market volatility, the **XGBoost model** demonstrated superior robustness, achieving a **Sharpe Ratio of 2.42** and a minimal Maximum Drawdown (MDD) of **0.037**, significantly outperforming the Linear Regression benchmark (Sharpe: -0.84)[cite: 47, 342, 341].

**Tools & Skills:** Python (Pandas, Scikit-learn, XGBoost), High-Frequency Data Analysis, Quantitative Modeling, Financial Time Series.
