# 📊 Trader Behavior Analysis using Market Sentiment

##  Objective
Analyze how Bitcoin market sentiment (Fear/Greed) affects trader behavior and performance on Hyperliquid.

---

##  Datasets
1. Market Sentiment Dataset (Fear/Greed Index)
2. Historical Trader Data (Hyperliquid)

---

##  Methodology
- Cleaned and standardized both datasets
- Converted timestamps to daily format
- Merged datasets using date alignment
- Created features:
  - Win rate (profit > 0)
  - Trade size (risk proxy)
  - Trade frequency
- Performed sentiment-based analysis

---

##  Key Insights
1. Traders take **larger positions during Greed**, indicating higher risk appetite  
2. **Win rate is higher during Greed**, suggesting favorable market conditions  
3. Fear periods show **more conservative trading behavior**

---

##  Strategy Recommendations
- Reduce trade size during Fear markets  
- Increase participation during Greed markets  
- Use sentiment as a signal for risk adjustment  

---
##  How to Run

### 1️ Install dependencies

pip install pandas numpy matplotlib seaborn

## 2️ Run notebook

jupyter notebook analysis.ipynb

