# Trading Data Analysis & Backtesting

## Project Overview

This project is aimed at analyzing options trading data and performing various tasks such as descriptive statistics, data cleaning, filtering, and visualizing trends. Additionally, a simple backtesting strategy for buying and selling call options is implemented. The tasks are performed using Python, leveraging libraries such as `pandas` for data manipulation and `matplotlib` for visualizations.

### Datasets Used
1. **Nifty Tick Data**: Contains information about tick data for Nifty, including open, close, and volume prices.
2. **Option Chain Data**: Provides details about options trading, including strike price, volume, and open interest for call and put options.

---

## Key Features

### Task 1: Data Import & Basic Analysis
- Import and clean two CSV datasets (`nifty_tick_data.csv` and `option_chain_tick_data.csv`).
- Provide basic descriptive statistics (mean, median, min, max) for key columns:
  - **Nifty Tick Data**: Open, Close, Volume
  - **Option Chain Data**: Strike Price, Volume, Open Interest

### Task 2: Volume Calculation by Option Type
- Calculate the total volume for each option type (Call/Put).

### Task 3: Data Cleaning & Formatting
- Remove rows with missing data and inconsistent values.
- Ensure `Timestamp` is in the correct format (`YYYY-MM-DD`) and chronologically sorted.

### Task 4: Data Filtering
- Filter the data for options with:
  - Strike Price > 15000
  - Volume > 100

### Task 5: Visualizations
- Create a time-series plot showing the trend of the Strike Price(Last Traded Price (LTP)) for a specific option.
- Visualize open interest for Call and Put options over time for the last expiry.

### Task 6: Backtesting Strategy
- Implement a backtesting rule for buying a Call option when the Strike Price(Last Traded Price (LTP)) increases by 5% within a 10-minute window.
- Calculate and plot the performance of the strategy.

---

## Technologies Used

- **Python**: Core programming language for data processing and analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib**: For creating visualizations.
- **NumPy**: For numerical operations.
- **Datetime**: For handling date and time.

---

## Setup & Installation

### Prerequisites
- Python 3.x
- The following Python libraries must be installed:
  - `pandas`
  - `matplotlib`
  - `numpy`
