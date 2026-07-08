# Portfolio Risk Analysis

Portfolio risk analysis of a 70% stock and 30% bond ETF portfolio using daily U.S. market data from 2010 to 2024.

The project evaluates return, volatility, drawdowns, diversification, benchmark performance, stress periods, regression exposure and allocation sensitivity.

## Portfolio

The baseline portfolio includes:

| ETF | Weight | Role |
|---|---:|---|
| SPY | 50% | Broad U.S. equity |
| QQQ | 15% | Growth equity |
| IWM | 5% | Small cap equity |
| IEF | 20% | Intermediate Treasury bonds |
| TLT | 10% | Long term Treasury bonds |

## Analysis

The project includes:

- Portfolio return and volatility analysis
- Maximum drawdown and annual return review
- Correlation and risk contribution analysis
- Benchmark comparison against SPY
- Historical stress testing
- Regression exposure model
- Allocation sensitivity analysis

## Tools

Python, Pandas, NumPy, Matplotlib, portfolio analytics, financial time series analysis.

## Output

The final PDF report is available in the `report` folder.

## Key Findings

The 70/30 portfolio delivered solid risk adjusted performance from 2010 to 2024.

Diversification helped reduce volatility and drawdowns compared with SPY, although it also lowered total return.

Treasury exposure supported the portfolio in most stress periods, but protection weakened in 2022 when stocks and bonds declined together.

Sensitivity analysis shows the main tradeoff between higher stock exposure and higher bond exposure.
