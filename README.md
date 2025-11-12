# 📊 Portfolio Analysis Challenge

This project was developed as part of a practical data analysis assignment focused on **portfolio performance and risk evaluation** using Python.

The goal was to analyze a set of financial assets, calculate their returns and correlations, evaluate the portfolio’s risk–return performance, and visualize its composition over time.

---

## 🧠 Objectives
1. Load and visualize historical asset prices.  
2. Calculate **daily percentage returns** and analyze correlations.  
3. Evaluate **portfolio performance** through cumulative returns, annualized return, and volatility.  
4. Analyze **asset allocation by category** (Fixed Income, Equity, Alternative).  
5. Provide a **final financial recommendation** based on findings.

---
## 📂 Project Structure

```
Portfolio-Analysis/
│
├── Data/ # Raw datasets
│ ├── asset_price_data.csv
│ ├── portfolio_weights.csv
│ └── asset_information_data.csv
│
├── Notebook/ # Jupyter notebooks with analysis
│ └── Tech-Challenge.ipynb
│
├── Visualizations/ # Exported plots and charts
│ ├── asset_price_evolution.png
│ ├── correlation_matrix.png
│ ├── scatter_equities.png
│ ├── cumulative_portfolio_returns.png
│ ├── asset_weights.png
│ └── weights_by_family.png
│
├── main.py # Script for future modular implementation
├── pyproject.toml # Dependencies and environment setup
├── uv.lock # Locked dependency versions
└── README.md # Project documentation
```


## 🧰 Tools & Libraries
- **Python 3.13**
- **Pandas**, **Matplotlib**, **Seaborn**
- **Jupyter Notebook**
- **Git & GitHub** for version control

**Data files used:**
- `Data/asset_price_data.csv`
- `Data/portfolio_weights.csv`
- `Data/asset_information_data.csv`

📂 `visualizations/`  
*includes cumulative returns, correlation heatmap, and allocation charts.*

---

## 📈 Key Findings
- **Annualized Return:** 11.42%  
- **Annualized Volatility:** 8.82%  
- **Sharpe-like ratio:** ≈ 1.29 → strong risk-adjusted performance.  
- The portfolio shows **solid diversification** across Fixed Income, Equity, and Alternatives.  
- It recovered strongly after the 2020 downturn and maintained long-term growth.

---

## 🏦 Asset Categories Explained

The portfolio consists of three main asset classes, each serving a different purpose in risk and return balance:

| **Asset Type** | **Examples** | **Role in Portfolio** |
|-----------------|--------------|------------------------|
| **Fixed Income** | Certificates of Deposit (CDs), government or corporate bonds | Provides stability and predictable income through fixed interest payments |
| **Equity** | Stocks, ETFs | Represents company ownership; higher potential returns but more volatility |
| **Alternative** | Bitcoin, gold, real estate, hedge funds | Adds diversification; returns are often uncorrelated with traditional markets |

💡 *Example:* A Certificate of Deposit would be classified as **Fixed Income**,  
buying company shares would fall under **Equity**,  
and investing in Bitcoin would be considered an **Alternative** asset.

---

## ⚖️ Price Normalization Rationale

Because each asset had a different nominal value (e.g., stocks, bonds, and Bitcoin priced in different ranges),  
all price series were **normalized to 1 at the starting date** to allow fair comparison.

This means each line in the price evolution chart represents **relative performance** instead of absolute price levels.  
It makes trends visible regardless of the asset’s initial price, highlighting which categories performed better over time.

---


## 💬 Financial Recommendation
The current portfolio strategy is **effective and well-balanced**.  
It offers strong returns with moderate risk, making it suitable for long-term investors such as a **couple with medium to high risk tolerance**.

**Recommendations:**
- ✅ Maintain the current diversification structure.  
- ⚖️ Slightly increase **Fixed Income** allocation during high volatility periods.  
- 🔁 **Rebalance annually** to keep consistent exposure and risk levels.

---

## 🖼️ Project Visuals

Main plots generated in this analysis are saved under  
`visualizations/` and include:

1. **Asset Price Evolution (Normalized)**  
2. **Daily Returns Correlation Matrix**  
3. **Scatter Plot: Equity vs. Equity**  
4. **Cumulative Portfolio Returns**  
5. **Asset Weights by Family**

---

## 🎤 Presentation Slides
📎 **Google Slides Presentation:**  
👉 [View Slides](https://docs.google.com/presentation/d/1xx09CtmPviXYvznnmSW6VV1z6QFfGax2-8PJJMVXCfE/present?slide=id.p)

---

## 👩‍💻 Author
**Irma Fernández Wiechers**  
Ironhack Data Analytics Bootcamp — Berlin, 2025  
🔗 [GitHub: irmacfw](https://github.com/irmacfw)
