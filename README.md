# 📊 Markowitz Portfolio Simulation – Risk & Return Analysis (S&P 500)

This project implements a portfolio analysis system based on the **Markowitz Modern Portfolio Theory**, using 5 years of S&P 500 stock data. It focuses on exploring the relationship between **risk (covariance)** and **return (profit)** across randomly generated portfolios.

---

## 📁 Project Structure

- `cleaned_stocks.csv` – Preprocessed dataset (S&P 500 stock prices)
- `portfolioConstruction.ipynb` – Simulates 10 random portfolios and plots growth
- `portfolio_avg_cov_vs_profit.csv` – KPI summary (covariance vs. final value)
- `portfolio_growth.csv` – Portfolio values over time (ready for Power BI)
- `portfolios.json` – The list of selected stocks for each portfolio
- `portfolio_stock_list.csv` – Readable stock list per portfolio
- `PowerBI visuals` – Visual analysis of results (screenshots / PBIX file)

---

## 🎯 Objectives

1. **Clean and preprocess** S&P 500 data (5-year period)
2. **Simulate** 10 portfolios with 10 random stocks each
3. **Track performance** over time, assuming a $10,000 investment
4. **Analyze average stock covariance** within each portfolio
5. **Compare profit vs. covariance** using Power BI

---

## 🧠 Key Insight

Portfolios with higher internal stock covariance, such as **Portfolio 9**, tended to produce higher profits — suggesting that under certain market conditions, strong correlation between stocks may still lead to superior performance.

---

## 🛠 Technologies Used

- Python (Pandas, NumPy, Matplotlib)
- Power BI
- Git & GitHub

---

## 🤖 Credits

This project was developed with guidance and support from **ChatGPT**, used for code generation, explanation, and report drafting.

---

## 📌 Future Work

- Add Sharpe Ratio and volatility comparison
- Build efficient frontier
- Sector-based diversification analysis
