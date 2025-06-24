# 📊 Trader Behavior Insights Based on Market Sentiment

📌 Overview

This project explores how trader behavior and profitability vary with **Bitcoin market sentiment**—classified as *Fear* or *Greed*. The analysis uses historical trading data from Hyperliquid alongside a fear/greed sentiment index.

This was completed as part of an application for the **Junior Data Scientist** role with Bajarangs/PrimeTrade.


📁 Datasets Used

1. **Historical Trader Data**  
   Columns: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `Closed PnL`, `leverage`, etc.

2. **Bitcoin Market Sentiment Index**  
   Columns: `date`, `classification (Fear/Greed)`

Objectives

- Merge and clean the datasets on a daily basis
- Explore the relationship between market sentiment and:
  - Trader profitability (Closed PnL)
  - Position size and trade behavior
  - Risk preferences (e.g., leverage, side)
- Provide actionable insigh

Key Findings

- **Average Closed PnL** was higher during *Greed*, suggesting traders performed better in bullish markets.
- **Trade sizes** were larger during *Greed*, showing greater risk appetite.
- **Sells during Fear** tended to be more profitable than buys.
- Box plots revealed wider variation in profit during *Greed* periods.
- `{X}` trades had no sentiment label due to missing index data (already excluded).
 
Visualizations

- **Boxplot of PnL by Sentiment**
- **PnL Trend Over Time**
- **Side-wise profitability (Buy/Sell)** under different sentiment regimes

Tech Stack

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- GitHub
 
Live Notebook

👉 View the full notebook here: [LINK TO YOUR .ipynb ON GITHUB]

---

## 🙋‍♂️ About Me

**Devansh Sawhney**  
AI & Data Science Enthusiast  
📧 devanshsawhney20@gmail.com  
[LinkedIn](https://www.linkedin.com/in/devansh-sawhney-77a69121b/)

---
