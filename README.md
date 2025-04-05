# Climate Change Analysis

## Project Overview
This project presents an in-depth data analysis and time series forecasting study on **global surface temperature** and **CO₂ emissions**. The goal is to uncover key patterns, understand the impact of greenhouse gases on climate change, and forecast future temperature trends using statistical and machine learning models.
- **Tools & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, scikit-learn, TensorFlow (Keras), Prophet
- **Techniques:** EDA, Time Series Forecasting, Hypothesis Testing, Correlation Analysis, Change Point Detection

## Data Sources
This project primarily uses two data sources
- Global Surface Temperature Anomaly (1850-2024) [GISTEMP v4](https://data.giss.nasa.gov/gistemp/)
- Global CO₂ Emissions (1850-2023) [CO₂ Emissions](https://ourworldindata.org/co2-emissions)

## Key Insights & Findings
- **Data Exploration:** Conducted comprehensive EDA on Global Surface Temperature and CO₂ datasets, analyzing data types, missing values, duplicates, and outliers. Used statistical imputation and interpolation to clean the data.
- **Temperature Trend**

  ![Global Temperature Anomaly](https://github.com/balaji-in-kaggle/Climate_Change_Analysis/blob/main/image/Global%20Temperature%20Anomaly.png)
- **Time Series Forecasting:** Modeled temperature anomalies using:
  - **SARIMA**
  - **LSTM (Long Short-Term Memory Neural Network)**
  - **Prophet**
  - Final model: **SARIMAX**, chosen based on performance and reliability.

   ![Forecasted Temperature](https://github.com/balaji-in-kaggle/Climate_Change_Analysis/blob/main/image/Forecasted%20Temperature.png)

- **Hypothesis Testing:** Revealed that global warming follows a **quadratic trend** (accelerating change) rather than a constant rate.

  ![Quadratic model](https://github.com/balaji-in-kaggle/Climate_Change_Analysis/blob/main/image/Accelerated%20Global%20Warming.png)

- **Change Point Detection (CPD):** Identified a significant acceleration in global warming **from 1989 to 2024** using CPD techniques.
  
  ![Change Point Trend](https://github.com/balaji-in-kaggle/Climate_Change_Analysis/blob/main/image/Change%20Point%20Trends.png)
  
- **Correlation Analysis:** Found a strong correlation between **CO₂ emissions** and **rising global temperatures**, confirming CO₂ as the dominant contributor to greenhouse gas effects.

  ![CO2 Correlation](https://github.com/balaji-in-kaggle/Climate_Change_Analysis/blob/main/image/CO2%20Correlation.png)

---

## 📂 Project Structure
