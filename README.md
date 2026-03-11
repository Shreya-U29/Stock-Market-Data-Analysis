# 📈 Stock Market Data Analysis & Dashboard – Python Project

## 📌 Project Overview

This project analyzes **historical stock market data of major technology companies** to understand price trends, market behavior, and stock correlations. The project combines **Exploratory Data Analysis (EDA)** with an **interactive Streamlit dashboard** to visualize stock performance and technical indicators.

The analysis focuses on major technology companies such as:

* Apple (AAPL)
* Amazon (AMZN)
* Google (GOOG)
* Microsoft (MSFT)

The goal is to identify **stock price trends, daily returns, moving averages, and correlations between major tech stocks**.

---

# 📊 Data Source

The dataset consists of **historical stock market data for S&P 500 technology companies**, including daily trading information.

### Key Features in the Dataset

* `date` – Trading date
* `open` – Opening stock price
* `high` – Highest price during the day
* `low` – Lowest price during the day
* `close` – Closing stock price
* `volume` – Number of shares traded
* `Name` – Company name

Each company dataset contains **5 years of historical stock market data**.

---

# 🛠 Tools & Technologies Used

### Programming

* **Python**

### Data Analysis

* **Pandas**
* **NumPy**

### Visualization

* **Matplotlib**
* **Seaborn**
* **Plotly**

### Dashboard Development

* **Streamlit**

---

# 🔍 Analysis Performed

## 1️⃣ Stock Price Trend Analysis

Analyzed **closing price trends over time** to observe how stock prices evolved across different years.

Key insights:

* Identified long-term growth patterns in major tech companies
* Observed periods of rapid price growth and decline

---

## 2️⃣ Moving Average Analysis (Technical Indicator)

Calculated **moving averages** to smooth price fluctuations and identify trends.

Moving averages used:

* **10-day Moving Average**
* **20-day Moving Average**
* **50-day Moving Average**

Purpose:

* Detect short-term and long-term trends
* Identify potential bullish or bearish patterns

---

## 3️⃣ Daily Return Analysis

Calculated **daily percentage returns** using:

```
Daily Return = Percentage change in closing price
```

This helps measure:

* Day-to-day stock volatility
* Market risk and fluctuation patterns

---

## 4️⃣ Time-based Resampling Analysis

Stock prices were **resampled to different time frequencies**:

* Monthly
* Quarterly
* Yearly

This helps observe **long-term stock performance trends** and reduce daily noise.

---

## 5️⃣ Multi-Stock Correlation Analysis

Compared stock performance across companies using a **correlation heatmap**.

Companies compared:

* Apple
* Amazon
* Google
* Microsoft

The correlation matrix helps identify:

* Stocks that move together
* Market relationships between major tech companies

---

# 📊 Interactive Stock Dashboard

An **interactive Streamlit dashboard** was built to allow users to explore stock data dynamically.

### Dashboard Features

✔ Select different companies from sidebar
✔ Visualize stock price trends
✔ View moving averages
✔ Analyze daily returns
✔ Switch between monthly / quarterly / yearly price trends
✔ Compare stock correlations

---

# 📈 Key Insights

* Major tech stocks show strong long-term growth trends.
* Moving averages help smooth short-term volatility.
* Daily returns highlight periods of market instability.
* Some tech stocks show **strong correlation**, indicating similar market behavior.

---

# 🚀 Skills Demonstrated

* Financial Data Analysis
* Exploratory Data Analysis (EDA)
* Technical Indicator Analysis
* Data Visualization
* Interactive Dashboard Development
* Python for Financial Analytics

---

# 🎯 Project Outcome

This project demonstrates how **Python can be used to analyze financial market data and build interactive dashboards for stock analysis**. By combining **data analysis with visualization and dashboards**, the project provides insights into stock price behavior, volatility, and relationships between major tech companies.
