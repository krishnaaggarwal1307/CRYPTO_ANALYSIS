# CRYPTO_ANALYSIS
# Crypto Sentiment Analysis: Fear & Greed vs. Trader Behavior

## 📌 Project Overview
This project analyzes the relationship between market sentiment (using the **Crypto Fear & Greed Index**) and on-chain trader performance. By aligning historical trade data with sentiment scores, we identify how "Fear" and "Greed" impact profitability, trade frequency, and risk management across different trader segments.

## 📊 Key Insights

### 1. The "Fear" Paradox (High Stakes)
* **Finding**: Average Daily PnL is **25% higher** during "Fear" periods compared to "Greed" periods.
* **Insight**: Market panic creates extreme volatility that skilled traders exploit for outsized gains. However, while the *average* is higher, the *median* is lower, meaning Fear days produce a "winner-takes-all" environment with high risk of total loss for the average user.

### 2. The "Greed" Efficiency
* **Finding**: Frequent traders reach their peak win rate (**44%**) during "Greed" cycles.
* **Insight**: Upward-trending, optimistic markets are more predictable. This is the best environment for active traders to maintain high win rates through trend-following strategies.

### 3. Contrarian Behavior (The "Dip Buyers")
* **Finding**: Traders on this platform exhibit a strong **Long Bias** during Fear.
* **Insight**: As market sentiment drops, "Buy" orders and position sizes increase. Users are not chasing momentum; they are actively "buying the dip" when the index signals Extreme Fear.

## 💡 Strategic Recommendations

### Rule 1: The "Greed" Consistency Play
* **Market Condition**: Greed / Extreme Greed.
* **Action**: Maintain high trade frequency and standard position sizes. Focus on **Trend Following**, as this is the highest-probability environment for steady growth.

### Rule 2: The "Fear" Volatility Protocol
* **Market Condition**: Fear / Extreme Fear.
* **Action**: **Reduce trade size by 50%**. While Fear offers the biggest profit potential, the probability of failure is higher. Protecting capital is more important than "catching the bottom" with full leverage.

## 🛠️ Methodology & Tech Stack
- **Python**: Core analysis and data processing.
- **Pandas**: Data cleaning and daily alignment of datasets.
- **Matplotlib/Seaborn**: Visualizing PnL distributions and behavioral shifts.
- **Segmentation**: Traders were categorized into **Frequent** vs. **Infrequent** groups based on daily activity to isolate professional-style behavior from retail behavior.

## 📁 Repository Structure
- `analysis.ipynb`: The primary Jupyter Notebook containing data cleaning and analysis.
- `charts/`: Visual exports (PnL Distribution, Win Rate by Segment, Long/Short Bias).
- `historical_data.csv`: (Required) Raw trading data.
- `fear_greed_index.csv`: (Required) Daily sentiment index data.

  ## 📊 Analysis Visualizations

### 1. Daily PnL Distribution
![PnL Distribution](https://github.com/krishnaaggarwal1307/CRYPTO_ANALYSIS/blob/main/dailt%20pnl%20distribution%20by%20sentiment.png)

### 2. Win Rate by Segment
![Win Rate Segments](https://github.com/krishnaaggarwal1307/CRYPTO_ANALYSIS/blob/main/win%20rate%20by%20sentiment.png)

### 3. Trader Long Bias
![Long Bias](https://github.com/krishnaaggarwal1307/CRYPTO_ANALYSIS/blob/main/average%20long%20bias%20by%20sentiment.png)

### 4. Average daily trades
![daily trades](https://github.com/krishnaaggarwal1307/CRYPTO_ANALYSIS/blob/main/average%20daily%20trades%20by%20sentiment.png)
## 🚀 How to Run
1. Clone the repository:
   ```bash
git clone [https://github.com/krishnaaggarwal1307/CRYPTO_ANALYSIS.git](https://github.com/krishnaaggarwal1307/CRYPTO_ANALYSIS.git)
   cd CRYPTO_ANALYSIS
