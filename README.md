**Objective:** The project aims to compare different investment strategies, namely Buy and Hold and Momentum Trading, applied to a portfolio of stocks and the S&P 500 index. The goal is to identify the most profitable strategy.

**Data:** Stock data from 2017 to 2021 was gathered for 30 stocks across three sectors (Consumer Staples, Healthcare, Communication Services) using the Yahoo Finance API. Additionally, S&P 500 data for 2022 was collected.

**Methodology:**
1.	**Data Preparation:** Historical stock prices were extracted, and return features were calculated.
2.	**Buy and Hold Strategy:** Cumulative returns were calculated by summing up all individual stock returns.
3.	**Momentum Trading Strategy:** This involved calculating rolling averages (8-day and 21-day) and generating buy/sell signals based on their crossover points.
4.	**Modern Portfolio Theory (MPT):**
     o Top 9 stocks were selected based on momentum trading returns.
     o Optimization model using Pyomo was built to determine the optimal portfolio allocation for maximizing returns while considering risk using Efficient Frontier.
5.	**Performance Comparison:** Buy and Hold and Momentum Trading strategies were applied to the optimized MPT portfolio and compared with the performance of the S&P 500 index using both strategies.

**Results:**

•	S&P 500 stocks performance was better than the portfolio selected.

•	S&P 500 Momentum trading strategy outperformed the buy-and-hold strategy.

•	The optimized MPT portfolio yielded reasonable returns, but the pandemic significantly impacted its performance.

**Conclusion:**

•	While the initial focus was on Buy and Hold for long-term investments, the analysis suggested that Momentum trading could be a viable long-term strategy.

•	External factors, like the pandemic, can heavily influence stock performance.

•	Choosing optimal risk levels is crucial for balancing returns and potential losses.

