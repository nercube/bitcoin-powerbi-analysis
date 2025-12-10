# Bitcoin Power BI Analysis

## 📌 Project Overview
This project is an end-to-end **Power BI analytics dashboard** built using historical **Bitcoin daily market data (2014–2025)**.  
The goal of this project is to analyze Bitcoin’s market behavior through **price trends, trading volume, volatility, seasonality, and market sentiment**, and present the insights using interactive and well-structured dashboards.

The project demonstrates **real-world data analytics workflow** including data preparation, DAX calculations, dashboard design, and insight generation.

---

## 🎯 Business Objective
The primary objectives of this project are:
- To understand long-term Bitcoin price trends
- To analyze trading volume as an indicator of market participation
- To identify high-risk (volatile) periods
- To study monthly seasonal patterns
- To classify market behavior into bullish and bearish phases
- To present insights in a professional, presentation-ready format

---

## 📂 Dataset Description
The dataset contains **daily Bitcoin historical data** covering the period **2014 to 2025**.

### Columns Used:
- **Date** – Trading date (daily frequency)
- **Open** – Bitcoin price at the start of the day
- **High** – Highest price during the day
- **Low** – Lowest price during the day
- **Close** – Bitcoin price at the end of the day
- **Volume** – Total trading volume for the day

> Only Bitcoin data is used in this project. No other cryptocurrencies are included.

---

## 🧹 Data Preparation & Transformation
Data preparation was performed inside **Power BI Desktop**:

- Converted the `Date` column to proper date format
- Created calendar-related columns:
  - `Year`
  - `Month`
  - `Month Number`
- Sorted `Month` using `Month Number` for correct chronological order
- Verified data consistency and removed aggregation issues
- Ensured correct summarization rules:
  - **Prices → Average / Max**
  - **Volume → Sum**

---

## 📊 DAX Calculations Used
Several calculated columns and measures were created to support analytical requirements:

### Key Measures & Columns:
- **Average Close Price**
- **Maximum High Price**
- **Total Trading Volume**
- **Daily Volatility (High − Low)**
- **Average Daily Change (Close − Open)**
- **Market Type (Bull / Bear classification)**
- **30-Day Moving Average**
- **90-Day Moving Average**

These calculations enable trend analysis, risk assessment, and market sentiment classification.

---

## 🧠 Dashboard Structure (10 Pages)

### 📄 Page 1 – Executive Overview
- High-level KPIs
- Long-term Bitcoin price trend
- First-look summary for decision makers

### 📄 Page 2 – Price Trend Analysis
- Bitcoin closing price over time
- Identification of bull and bear cycles

### 📄 Page 3 – Volume Trend Analysis
- Trading volume over time
- Year-wise total volume comparison

### 📄 Page 4 – Year-wise Price Performance
- Average closing price by year
- Maximum yearly price (peaks)

### 📄 Page 5 – Monthly Seasonality Analysis
- Average price behavior by month
- Year × Month heatmap for seasonal patterns

### 📄 Page 6 – Volatility Analysis
- Daily price range to assess market risk
- Volatility spikes over time
- Volatility vs trading volume relationship

### 📄 Page 7 – Open vs Close Behavior
- Comparison of opening and closing prices
- Annual average daily price change

### 📄 Page 8 – Bull vs Bear Market Analysis
- Classification of trading days as Bull or Bear
- Distribution and trend visualization

### 📄 Page 9 – Moving Average Trend Context
- 30-day and 90-day moving averages
- Trend smoothing (not forecasting)

### 📄 Page 10 – Insights & Conclusion
- Key observations
- Risk and analysis notes
- Final business-style summary

---

## 📈 Key Insights
- Bitcoin shows strong long-term growth with extreme short-term volatility
- High trading volumes often accompany volatile price movements
- Certain months display recurring seasonal behavior
- Bullish days slightly dominate over bearish days in the long run
- Moving averages clearly highlight market trends without predicting future prices

---

## ⚠️ Limitations
- Analysis is based only on historical price and volume data
- External factors such as news, regulations, or macroeconomic indicators are not included
- No price forecasting is performed

---

## 🛠 Tools & Technologies Used
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Time-Series Analysis**
- **Financial Data Analysis**
- **Data Visualization Best Practices**

---

## 📁 Repository Contents
- `Bitcoin_Dashboard.pbix` – Power BI dashboard file
- `Bitcoin_PowerBI_Industry_Level_Report.pdf` – Detailed industry-level report
- `Bitcoin_PowerBI_Detailed_Report.pdf` – Step-by-step project explanation
- `README.md` – Project documentation

---

## 🎤 Interview Talking Point
> “This project demonstrates my ability to convert raw financial time-series data into a multi-page analytical dashboard using Power BI, focusing on trends, volatility, seasonality, and market behavior.”

---

## 🚀 Conclusion
This project represents a **complete Power BI analytics workflow** suitable for:
- Internship & placement evaluation  
- Resume & portfolio showcasing  
- Technical interviews  

It reflects both **technical competence** and **business-oriented analytical thinking**.

---
