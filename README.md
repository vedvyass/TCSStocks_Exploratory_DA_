# 📈 TCS Stock Market Analysis (EDA)

This is my second Data Science project! 

In this project, I performed an **Exploratory Data Analysis (EDA)** on TCS (Tata Consultancy Services) stock data. My goal was to move beyond simple Excel charts and use Python to uncover deeper insights about trends, risk, and volatility.

## 🎯 Project Goals
1.  **Clean the Data:** Handle date formatting and set proper indexes.
2.  **Analyze Trends:** Use Moving Averages (50-day and 100-day) to identify market direction.
3.  **Assess Risk:** Calculate Volatility to understand how risky the stock was during 2018-2019.
4.  **Distribution:** Visualize daily returns to see the stability of the stock.

## 🛠️ Tech Stack
* **Python:** The core language.
* **Pandas:** For data manipulation and time-series filtering.
* **Matplotlib:** For visualizing the trends and histograms.
* **Numpy:** For statistical calculations.

## 📊 Key Insights from My Analysis
* **Moving Averages:** By plotting the 50-day vs 100-day SMA, I could see clear "Golden Cross" moments where the trend turned positive.
* **Volatility:** The volatility graph showed specific spikes, indicating periods of high market uncertainty.
* **Daily Returns:** The histogram of daily returns formed a normal distribution, suggesting that extreme price crashes were rare for TCS during this period.

## ⚙️ How to Run This
1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/dwaipayandas18/tcs-stock-analysis.git](https://github.com/dwaipayandas18/tcs-stock-analysis.git)
    ```
2.  **Install Requirements:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the Script:**
    ```bash
    python main.py
    ```
    *(The graphs will pop up one by one. Close a graph to see the next one!)*

---
*Created by Dwaipayan Das*
