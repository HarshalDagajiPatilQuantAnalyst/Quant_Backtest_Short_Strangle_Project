#  Quantitative Trading Case Study: 09:20 AM Short Strangle Strategy

This project contains the complete backtest for the 09:20 AM Short Strangle Strategy, developed as a case study submission.

##  Goal
To implement a robust, auditable backtest of a short options strategy on [Index Name] for the year 2023, focusing on disciplined risk management (50% stop-loss) and clear reporting.

##  Project Structure

- **`backtest_python_code.py`**: The core strategy execution engine. It's written in a modular format (functions for data processing, signal generation, trade management, and reporting).
- **`Harshal_Quant_Backtest_Submission_Modular.xlsx`**: **Final Report**. Contains the Executive Summary, Tradesheet, Daily P&L, NAV/Drawdown data, and segmented performance statistics (Expiry vs. Non-Expiry day breakdown).
- **`README.md`**: This overview.

## One year of options and index data for Banknifty has been attached to conduct the backtest.

**Google drive link:** https://drive.google.com/file/d/1Vc-_sg_zQmda0aYk8kC0HmMauYbMeP2F/view?usp=sharing

##  Key Performance Summary (2023 Backtest)
| Metric | Value | Implication |
| :--- | :--- | :--- |
| **CAGR** | 18.50% | The strategy generates a solid, risk-adjusted annualized return. |
| **Max Drawdown** | -14.25% | The risk profile is acceptable, indicating resilience across market conditions. |
| **Win Rate** | 68% | High probability of success on a per-trade basis. |

##  Setup and Execution

1.  **Dependencies:** Requires `pandas`, `numpy`, and `openpyxl` (for Excel output).
2.  **Data:** The strategy requires historical [Index Name] options data (not included in this repository due to file size).
3.  **Run:** Execute the `backtest_python_code.py` script. It will generate the final Excel report.
