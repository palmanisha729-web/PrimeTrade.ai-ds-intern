# Trader Performance vs Market Sentiment Analysis

## 📌 Overview
This project analyzes the relationship between market sentiment (Fear/Greed) and trader behavior using historical trading data.

The goal is to identify patterns in trader performance and derive actionable trading strategies.

---

## 📊 Methodology

- Loaded and cleaned both datasets (sentiment and trading data)
- Standardized column names and handled missing values
- Created key metrics:
  - Profit & Loss (PnL)
  - Win rate
  - Trade size distribution
  - Buy/Sell ratio
- Performed exploratory data analysis using visualizations
- Segmented traders based on behavior (trade size, frequency)
- Built a simple predictive model to classify profitable trades

> Note: Due to mismatch in dataset time periods (2018 vs 2024), direct merging was not feasible. Hence, analysis was performed independently and insights were derived indirectly.

---

## 🔍 Key Insights

1. Trader profitability is inconsistent — a small number of large trades drive overall gains.
2. Trade size distribution is highly skewed, indicating poor risk management.
3. Traders show no clear directional bias (buy/sell nearly equal), suggesting reactive trading behavior.
4. Despite fear-dominant sentiment, traders take large positions, indicating overconfidence.

---

## 💡 Recommendations

- Reduce position sizes in volatile or fear-driven markets
- Apply strict risk management (stop-loss, risk-reward ratio)
- Avoid overtrading and focus on high-confidence setups

---

## 🤖 Predictive Modeling

- A Random Forest model was used to predict trade profitability
- Results suggest that trade size alone is not sufficient to predict outcomes
- Indicates need for more features (market conditions, timing, strategy)

---

## 📁 Files Included

- `notebook.ipynb` — complete analysis
- `README.md` — project summary

---

## 🚀 Conclusion

The analysis highlights that traders lack consistency and discipline. Improving risk management and adapting to market sentiment can significantly enhance trading performance.
