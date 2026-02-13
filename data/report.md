# Trader Performance vs Market Sentiment — Analysis Report

## Objective

The objective of this analysis is to understand how market sentiment affects trader performance and behavior. Specifically, we examined whether trader profitability, trade size, and trading activity differ across sentiment conditions such as Fear, Greed, and Extreme Greed.

---

## Methodology

### Data Preparation

* Loaded trader and sentiment datasets
* Checked for missing values and duplicates
* Converted timestamps into date format
* Merged datasets using the date column to align trader performance with market sentiment

### Key Metrics Created

* Average Profit (PnL)
* Win rate
* Average trade size
* Number of trades per sentiment
* Trader segmentation based on trade size

---

## Key Insights

### Insight 1: Profitability is highest during Extreme Greed

Trader profitability is highest during Extreme Greed sentiment. This suggests that bullish market conditions provide the best opportunities for profit.

### Insight 2: Trading activity increases during Fear and Greed

Trading frequency is highest during Fear and Greed sentiment periods. This indicates that traders become more active during volatile market conditions.

### Insight 3: Trade size is largest during Fear sentiment

Traders use larger trade sizes during Fear sentiment. This suggests traders take higher-risk positions during uncertain market conditions.

### Insight 4: Profitability is lowest during Neutral and Extreme Fear

Trader performance is lower during Neutral and Extreme Fear sentiment, indicating cautious trading behavior.

---

## Trader Segmentation

Traders were segmented based on trade size. High-size traders tend to generate higher profits, especially during Greed sentiment.

---

## Strategy Recommendations

### Strategy 1: Increase trading during Extreme Greed

Since profitability is highest during Extreme Greed sentiment, traders should increase trading activity and position sizes during bullish conditions.

### Strategy 2: Reduce risk during Extreme Fear and Neutral sentiment

Since profitability is lower during Extreme Fear and Neutral sentiment, traders should reduce trade size and focus on risk management.

### Strategy 3: Carefully exploit opportunities during Fear sentiment

Fear sentiment presents volatility-driven opportunities. Traders can take advantage of these conditions with controlled risk.

---

## Bonus: Predictive Model

A Random Forest model was trained using sentiment and trade size to predict profitability. The model showed that sentiment and trade size are useful predictors of trader performance.

---

## Conclusion

Market sentiment significantly affects trader performance and behavior. Traders perform best during Extreme Greed conditions and should adjust trading strategies based on sentiment to maximize profitability and minimize risk.

This analysis demonstrates how sentiment-driven trading strategies can improve decision-making.
