
## Apple Stock 5-Year Analysis (2019–2024)

This project analyzes the performance of Apple Inc.'s stock (\$AAPL) over a 5-year period using Python. It combines time series analysis, seasonal insights, and technical pattern detection to answer key trading and investment questions.

---

### What This Project Covers

#### 1. **Trend Analysis**

* Visualized the closing price from 2019 to 2024.
* Found an overall upward trend with a few sharp pullbacks.
* The highest closing price occurred in **Dec 2023**, while the lowest was in **March 2020**.

#### 2. **Volatility Breakdown**

* Calculated year-wise standard deviation of daily returns.
* **2020** was the most volatile year, aligning with COVID market disruptions.

#### 3. **Monthly Seasonality**

* Grouped average closing prices by month.
* **August, November, and January** showed stronger average performance.
* Used bar charts sorted in calendar order to highlight consistent seasonal trends.

#### 4. **Support and Resistance Levels**

* Applied local extrema detection using `scipy.signal` to find true **peaks** and **troughs**.
* Identified recurring support zones around **\$125–130** and resistance near **\$180+**.
* These levels suggest areas of historical buying/selling interest.

---

### Technical Stack

* `pandas`, `numpy` – for data manipulation
* `matplotlib`, `seaborn` – for visualization
* `yfinance` – for historical stock price data
* `scipy.signal` – to detect local turning points (peaks & troughs)

---

### File Included

* `apple_5yr_one.ipynb` – Full analysis, charts, and insights in one notebook.

---

### How to Use

1. Make sure the CSV file (`apple_5yr_one.csv`) is available in your working directory.
2. Install required packages:

   ```bash
   pip install pandas numpy matplotlib seaborn yfinance scipy
   ```
3. Open the notebook and run it cell by cell.

