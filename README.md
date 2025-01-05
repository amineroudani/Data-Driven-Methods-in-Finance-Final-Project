# A Multi-Factor Market-Neutral Investment Strategy for New York Stock Exchange Equities

## Overview
This repository contains all materials related to the report *"A Multi-Factor Market-Neutral Investment Strategy for New York Stock Exchange Equities"* by Georgios M. Gkolemis, Adwin Richie Lee, and Amine Roudani. The project presents a systematic, market-neutral, multi-factor investment strategy targeting equities traded on the New York Stock Exchange (NYSE).

## Abstract
This report presents a systematic market-neutral, multi-factor investment strategy for New York Stock Exchange equities with the objective of delivering steady returns while minimizing correlation with the market. A robust feature set is integrated combining momentum-based indicators, fundamental factors, and analyst recommendations. Using various statistical tests for feature selection, the strategy identifies key drivers of equity performance and ranks stocks to build a balanced portfolio of long and short positions. Portfolio construction methods, including equally weighted, risk parity, and minimum variance beta-neutral approaches, were evaluated through rigorous backtesting. Risk parity demonstrated superior performance with a higher Sharpe ratio, lower beta, and smaller maximum drawdown compared to the Standard and Poor's 500 index. Risk parity's market neutrality, combined with its ability to maintain steady returns and mitigate large drawdowns, makes it a suitable approach for managing significant capital in equity markets.

[Read the full report here](https://doi.org/10.48550/arXiv.2412.12350)


## Key Highlights
- **Point-In-Time Methodology**: Special attention was given to maintaining the integrity of point-in-time data throughout the analysis. This ensures that no future information leaked into the modeling or backtesting phases.
- **Robust Out-of-Sample Testing**: The results were validated using an untouched, 8-year out-of-sample dataset. This rigorous approach demonstrates the strategy's robustness and ability to deliver consistent performance across different market conditions.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/market-neutral-strategy.git
