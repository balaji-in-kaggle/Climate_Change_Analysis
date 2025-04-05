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


## Tableau Dashboard
Key insights and visualizations from this analysis have been published to Tableau Public, providing an interactive overview of global temperature anomalies, CO₂ emissions, and long-term climate trends for easy exploration and sharing. [Tableau Dashboard](https://public.tableau.com/app/profile/balaji.r7633/viz/NASA_1_17422296850330/Dashboard1)

## Contact
For any questions, suggestions, or feedback, feel free to open an issue in this GitHub repository.
