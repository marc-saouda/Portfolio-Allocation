# **Portfolio Allocation**

This project was developed as part of my work in the **HEC Investment Club** to explore strategies for portfolio optimization and rebalancing. The goal was to implement quantitative methods for analyzing and managing a portfolio of securities while optimizing metrics such as volatility and the Sharpe ratio.

---

## **Project Overview**
The portfolio optimization and rebalancing tool enables users to:
- Retrieve historical data for a portfolio of securities.
- Calculate key metrics such as returns, volatility, and the Sharpe ratio.
- Optimize portfolio weights to:
  - Maximize the Sharpe ratio.
  - Minimize portfolio variance.
- Visualize results with correlation heatmaps, historical return scatter plots, and the efficient frontier.

This project uses real-world data from Yahoo Finance.

---

## **Features**
1. **Data Analysis:**
   - Historical price data retrieval using `yfinance`.
   - Daily returns, covariance matrices, and expected returns calculation.

2. **Optimization:**
   - Maximize Sharpe ratio using constraints on individual security weights.
   - Minimize variance to create a low-risk portfolio.
   - Supports custom constraints and bounds on portfolio weights.

3. **Visualization:**
   - **Correlation Heatmap:** Explore relationships between securities.
   - **Efficient Frontier Plot:** Evaluate risk-return trade-offs.
   - **Historical Performance Comparison:** Compare portfolio returns with market benchmarks.

4. **Customizable Portfolio Management:**
   - Add or remove securities dynamically.
   - Adjust portfolio weights or expected returns manually.

---

## **Libraries Used**
- **`pandas`**: Data manipulation and analysis.
- **`numpy`**: Numerical computations.
- **`yfinance`**: Retrieving financial market data.
- **`matplotlib`** and **`seaborn`**: Data visualization.
- **`scipy.optimize`**: Optimization of portfolio weights.

