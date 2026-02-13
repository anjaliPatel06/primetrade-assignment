# Trader Performance vs Market Sentiment Analysis

## Overview

This project analyzes how market sentiment (Fear, Greed, Extreme Fear, Extreme Greed, Neutral) affects trader behavior and profitability. The goal is to identify patterns in trader performance and provide actionable trading strategies based on sentiment conditions.

This analysis was completed as part of the Primetrade.ai Data Science Internship assignment.

---

## Dataset Description

Two datasets were used:

### 1. Market Sentiment Dataset

Contains daily Bitcoin market sentiment.

Columns:

* date: Date of sentiment
* sentiment: Market sentiment category
* value: Sentiment score

### 2. Trader Dataset

Contains detailed trading activity.

Important columns:

* Account: Trader ID
* Execution Price: Trade price
* Size USD: Trade size in USD
* Side: Buy/Sell
* Closed PnL: Profit or Loss
* Timestamp IST: Trade time

---

## Project Structure

```
primetrade_assignment/
│
├── notebook.ipynb        # Main analysis notebook
├── README.md             # Project documentation
├── report.md             # Insights and recommendations
└── data/
    ├── sentiment.csv
    └── trader_data.csv
```

---

## Steps Performed

### Data Preparation

* Loaded both datasets
* Checked missing values and duplicates
* Converted timestamps to date format
* Merged datasets using date column

### Feature Engineering

Created key metrics:

* Daily PnL per trader
* Win rate
* Average trade size
* Number of trades per sentiment
* Long/Short ratio

### Analysis

* Compared profitability across sentiment categories
* Analyzed trader behavior changes
* Identified behavioral patterns

### Bonus

* Built a simple predictive model using Random Forest
* Clustered traders based on trade size and profitability

---

## How to Run

### Install dependencies

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run notebook

```
jupyter notebook
```

Open:

```
notebook.ipynb
```

Run all cells.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Author

Anjali Patel
Data Science Internship Candidate
