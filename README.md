Algorithmic Market Reconnaissance System
Owner: Dr. Brian Penrod, DBA Objective: Automated Intelligence Preparation of the Battlefield (IPB) for Futures Markets.

1. Executive Summary
This project automates the "Observe" and "Orient" phases of the OODA Loop for financial decision-making. Instead of relying on subjective chart reading, this system utilizes Python and the yfinance API to mathematically define market regimes before the opening bell.

2. Technical Capabilities
Regime Identification: Algorithms classify the market state (Balanced vs. Trending) using Overnight High/Low statistical control limits.


Volatility Analysis: Dynamic calculation of 14-Day ATR (Average True Range) to assess "Potential Energy" and market compression.

Momentum Logic: Integration of RSI and 200-SMA to triangulate Directional Probability (Trend vs. Mean Reversion).

3. The Strategy
This tool is designed to support a Market Neutral or Directional Volatility strategy. It enforces risk discipline by identifying "No Trade" zones (inside the Overnight Range) and highlighting high-probability breakout targets.

4. Technology Stack

Python: Core logic and automation.


Pandas: Data manipulation and time-series analysis.


YFinance: Real-time market data ingestion.

NumPy: Vectorized mathematical calculations.
