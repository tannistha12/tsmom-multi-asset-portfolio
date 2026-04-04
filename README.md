# 📈 Time-Series Momentum (TSMOM) Multi-Asset Portfolio Allocator

A systematic, rule-based trading strategy that dynamically scales exposure across asset classes based on the sign and strength of their own past returns (3–12 month rolling windows).

---

## Problem Statement - 

Traditional buy-and-hold portfolios maintain constant exposure regardless of market conditions. This leads to:

- Large drawdowns during market regime shifts  
- Poor adaptability to trend reversals  
- Inefficient risk allocation  

### Core Question - 

Can a fully systematic, data-driven **Time-Series Momentum (TSMOM)** framework:

- Detect trend persistence at the individual asset level  
- Rebalance dynamically (monthly)  
- Apply volatility-based position scaling

---

## What is Time-Series Momentum?

Time-Series Momentum evaluates **each asset independently**, based on its own historical performance.

### Strategy Logic -

- If its own past 12-month return is **positive** → You go **long** (buy or increase exposure).
- If its own past 12-month return is **negative** → You go **short** (sell or reduce exposure to zero/cash).

This is applied across:

- Equities  
- Bonds  
- Commodities  
- Currencies  

### Key Distinction

| Approach | Description |
|----------|-------------|
| Cross-Sectional Momentum | Compare assets against each other |
| Time-Series Momentum | Evaluate each asset independently |

---

## 📚 Reference -

Moskowitz, Ooi & Pedersen (2012)  
**Time Series Momentum**  
http://docs.lhpedersen.com/TimeSeriesMomentum.pdf
