# Global Temperature Datset Analysis

### Overview

This project performs an extensive analysis of global temperature data to identify long-term climate trends and patterns. The analysis involves data cleaning, visualization, and transformation, with an emphasis on handling missing values, outliers, and normalization. The project highlights key trends in global temperature fluctuations, shedding light on the impact of climate change over time.

### Dataset Information

The dataset used is Global Temperature Time Series, which contains monthly global temperature anomalies from 1880 to 2016. The dataset includes the following columns:

- Source: The dataset source (e.g., GCAG, GISTEMP).
- Date: The date the temperature was recorded.
- Mean: The average global temperature anomaly (in °C) for the given date.
- Year: The extracted year from the Date column.

### Features of the Analysis

Data Cleaning and Preprocessing
- Date Conversion: The Date column is converted to a datetime format, and the Year is extracted for further analysis.
- Handling Missing Data: Missing values in the Mean column are interpolated using a linear method.
- Outlier Detection: Outliers in the Mean column are identified using the Z-score method and can be removed based on the project needs.
- Normalization: The Mean column is normalized using Min-Max Scaling to standardize the data and enable fair comparison across years.

### Key Outputs

- Global Temperature Trend: The line plot shows global temperature trends from 1880 to 2016, highlighting major temperature fluctuations and shifts over time.
- Normalized Temperature Distribution: A histogram depicting the distribution of normalized temperature values.
- Correlation Matrix: A heatmap showing correlations between the numerical columns, helping to understand relationships between temperature and other environmental factors.

### Visualizations

- Global Temperature Trend: Line plot showing the global temperature trend over time, comparing the original and normalized temperature data.
- Temperature Distribution: Histogram of normalized temperatures with KDE (Kernel Density Estimation) to analyze the spread of temperature values.
- Correlation Heatmap: Heatmap showing correlations between numerical variables in the dataset, such as Year and Mean temperature anomaly.

##### Line plot showing global treads

![screenshot-github com-2025 01 27-13_05_05](https://github.com/user-attachments/assets/36eaa380-1a35-4d8c-b79d-a85226a9571b)

### Key Findings

- Global Temperature Trend: The data reveals a steady increase in global temperatures over time, with recent decades showing the most significant warming.
- Correlation between Year and Temperature: The dataset shows a strong positive correlation (0.82) between Year and the Mean temperature anomaly, suggesting that global temperatures have been rising consistently.
- Normalized Temperature Distribution: After normalization, the temperature values are scaled between 0 and 1, allowing for a more consistent comparison across years.

### Future Work

- Extended Analysis: Explore correlations with additional environmental factors such as CO2 emissions, sea level rise, or land use changes.
- Time Series Forecasting: Use time series models (ARIMA, LSTM, etc.) to predict future temperature trends based on historical data.
- Climate Change Modeling: Model the impact of various factors on global temperature and explore different climate change scenarios.

### Source

Dataset: [Global Temperature Dataset on Kaggle](https://www.kaggle.com/datasets/ianpetrustan/global-temperature-time-series)
