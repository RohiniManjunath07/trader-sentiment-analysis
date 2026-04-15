# 📊 Trader Performance vs Market Sentiment Analysis

A data analysis project exploring how **Bitcoin market sentiment (Fear/Greed)** influences **trader behavior and performance** on Hyperliquid.

This project uses **Python, Pandas, and data visualization** to uncover patterns and propose actionable trading strategies.

---

## ✨ Features

- 📊 Analyzed 200K+ trading records
- 🔗 Merged trader data with market sentiment data
- 📈 Calculated key metrics like PnL, win rate, trade frequency
- 🔍 Studied trader behavior under different sentiments
- 🧠 Segmented traders into meaningful groups
- 💡 Generated actionable trading strategies

---

## 🏗️ Project Structure

```
project/
│
├── trader_sentiment_analysis.ipynb
├── data/
│   ├── fear_greed_index.csv
│   └── trader_data.csv
│
├── outputs/
│
└── README.md
```

---

## 🚀 Objective

To analyze how **market sentiment (Fear vs Greed)** affects:

- Trader profitability (PnL)
- Win rate
- Risk behavior

Also to study how trader behavior changes in terms of:

- Trade frequency  
- Position size  
- Buy/Sell patterns  

---

## ⚙️ Methodology

### 1. Data Cleaning
- Removed duplicates  
- Handled missing values  
- Standardized column names  
- Converted timestamps to datetime  

### 2. Data Transformation
- Extracted date from timestamps  
- Merged trader data with sentiment dataset  

### 3. Feature Engineering
Created key metrics:

- Daily PnL per trader  
- Win rate  
- Average trade size  
- Trade frequency  
- Long/Short ratio  

### 4. Segmentation
Traders were categorized into:

- High vs Low trade size  
- Frequent vs Infrequent traders  
- Winners vs Losers  

---

## 📊 Key Insights

1. Traders tend to generate higher profits during **Greed** periods, indicating momentum-driven gains.

2. Larger trade sizes are associated with higher risk, especially during **Fear** periods.

3. Frequent traders show more consistent performance across changing market sentiment.

---

## 💡 Strategy Recommendations

1. Reduce position size during **Fear** periods to minimize losses.

2. Increase trading activity during **Greed** periods to take advantage of market trends.

3. Avoid large trades during uncertain or volatile market conditions.

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## ▶️ How to Run

1. Open the notebook in Google Colab  
2. Upload the datasets:
   - `fear_greed_index.csv`
   - `trader_data.csv`  
3. Run all cells step-by-step  

---

## 📦 Dataset Details

### Market Sentiment Data
- Date  
- Classification (Fear / Greed)

### Trader Data
- Account  
- Execution price  
- Trade size (USD)  
- Side (Buy/Sell)  
- Timestamp  
- Closed PnL  
- Fee  

---

## 🧪 Analysis Checklist

- [ ] Data cleaned and validated  
- [ ] Datasets merged correctly  
- [ ] Metrics calculated  
- [ ] Fear vs Greed comparison done  
- [ ] Segmentation completed  
- [ ] Insights generated  
- [ ] Strategies proposed  

---

## 📌 Conclusion

Market sentiment plays a significant role in influencing trading performance and behavior.  
Adapting trading strategies based on sentiment can help improve profitability and manage risk effectively.

---

## 👤 Author

Rohini M  

---

## 📎 Submission

This project is submitted as part of the **Data Science Intern Assignment – Primetrade.ai**.
