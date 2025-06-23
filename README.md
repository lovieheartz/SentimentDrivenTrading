# Sentiment-Driven Trading Strategy Optimization

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

## 📊 Harness Market Psychology to Optimize Trading Performance

This project analyzes the relationship between cryptocurrency market sentiment (Fear & Greed Index) and trading performance data to uncover actionable patterns and develop sentiment-aware trading strategies.
[![Preview](https://raw.githubusercontent.com/lovieheartz/repo/main/images/Flowchart.png)](https://github.com/lovieheartz/repo/raw/main/images/Flowchart.png)

## 🔑 Key Features

- **Sentiment-Performance Correlation**: Quantifies how market sentiment impacts trading outcomes
- **Leverage Optimization**: Identifies ideal leverage ratios for each market condition
- **Temporal Patterns**: Reveals optimal trading hours based on market psychology
- **Asset Rotation**: Determines best-performing assets for each sentiment condition
- **Risk Management**: Calculates risk-adjusted returns across market environments

## 🧠 Key Insights

### Performance by Market Sentiment
| Sentiment       | Avg PnL | Win Rate | Sharpe Ratio |
|-----------------|---------|----------|--------------|
| Extreme Fear    | $142.50 | 68.2%    | 1.81         |
| Fear            | $87.30  | 59.8%    | 1.40         |
| Neutral         | $15.20  | 52.1%    | 0.36         |
| Greed           | -$23.80 | 47.6%    | -0.45        |

### Optimal Trading Parameters
| Condition       | Best Leverage | Ideal Hours   | Position Size |
|-----------------|---------------|---------------|---------------|
| Extreme Fear    | 10-20x        | 22:00-02:00   | Medium        |
| Fear            | 5-10x         | 21:00-01:00   | Small-Medium  |
| Neutral         | 1-5x          | 08:00-11:00   | Large         |
| Greed           | >100x         | 03:00-06:00   | X-Small       |

### Profit Distribution
- **98% of profits** generated during Fear conditions
- **Extreme Fear periods** offer 2.18:1 profit/loss ratio
- **Greed periods** show consistent losses despite higher trade volume

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn

### Installation
```bash
# Clone repository
git clone https://github.com/lovieheartz/SentimentDrivenTrading.git

# Navigate to project directory
cd SentimentDrivenTrading
