# Global Temperature Datset Analysis

### Overview

This project performs a comprehensive analysis of global temperature anomalies over time to uncover long-term climate trends and fluctuations. The focus is on understanding how global temperatures have changed from 1880 to the present, with an emphasis on identifying major climate events, trends, and anomalies. The analysis includes data cleaning, visualization, and transformation techniques, providing insights into the impact of climate change over the years. The project considers the effects of extreme events (outliers) on temperature trends and investigates the relationship between key variables like temperature and year.

### EDA Questions

I want to answer the following questions:

1. What is the global trend in temperature anomalies over time?
2. How does the distribution of global temperature anomalies (normalized values) look?
3. What is the relationship between the year and global temperature anomalies?
4. How do the GISTEMP and GCAG datasets compare in terms of temperature anomalies?
5. What extreme temperature anomalies (both positive and negative) have occurred, and what years did they happen?
6. Can we predict future global temperature anomalies using historical data?
7. Have there been periods of rapid warming, such as a hockey-stick pattern?

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

1. **Global Temperature Trend**: A line plot showing the global temperature trend from 1880 to 2016, highlighting major temperature fluctuations and shifts over time.
2. **Normalized Temperature Distribution**: A histogram showing the distribution of normalized temperature values across the dataset.
3. **Correlation Matrix**: A heatmap that visualizes correlations between numerical columns, helping to understand relationships between temperature anomalies and other variables.
4. **Extreme Temperature Anomalies**: Insights into the years with the highest and lowest recorded anomalies, marking key points in global temperature history.
Annual Rate of Change**: A line plot showing the annual rate of change in global temperature anomalies, identifying periods of rapid warming.

### Visualizations

1. **Global Temperature Trend**: A line plot showing the global temperature trend from 1880 to 2016, highlighting major temperature fluctuations and shifts over time.
2. **Temperature Distribution**: A histogram and KDE (Kernel Density Estimation) of the normalized temperature values to analyze how the temperature anomalies are distributed.
3. **Correlation Matrix**: A heatmap that visualizes correlations between numerical columns, helping to understand relationships between temperature anomalies and other variables.
4. **GISTEMP vs. GCAG**: A line plot comparing temperature anomalies from the GISTEMP and GCAG datasets, showing how the two sources of data align over time.

##### Line plot showing global treads

![screenshot-github com-2025 01 27-13_05_05](https://github.com/user-attachments/assets/36eaa380-1a35-4d8c-b79d-a85226a9571b)

### Key Findings

- **Global Temperature Trend**: The data reveals a clear, steady increase in global temperatures over time, with recent decades showing the most significant warming. This aligns with the broader understanding of global climate change.

- **Correlation between Year and Temperature**: A strong positive correlation (0.82) between the Year and Mean temperature anomaly suggests that global temperatures have consistently risen over the years. This provides evidence of ongoing global warming.

- **Normalized Temperature Distribution**: After normalization, the temperature values are scaled between 0 and 1, allowing for a more consistent comparison across years without the influence of large temperature spikes or drops.

- **Extreme Temperature Events**: The year 2016 recorded the highest temperature anomaly, which is consistent with the significant warming seen in recent years. The year 1909 recorded the lowest temperature anomaly, which provides context for the cooler periods in Earth's climate history.

### Future Work

1. **Extended Analysis**: Investigate additional environmental factors such as CO2 emissions, sea level rise, and land use changes to see how they influence global temperature anomalies.

2. **Time Series Forecasting**: Use time series models (e.g., ARIMA, LSTM) to predict future temperature anomalies based on historical trends.

3. **Climate Change Modeling**: Model the potential impact of various factors (such as human activities and natural climate events) on future global temperature and explore different climate change scenarios.

4. **Regional Temperature Trends**: Investigate temperature anomalies by region to understand how global warming may be affecting different areas of the world.

### Source

Dataset: [Global Temperature Dataset on Kaggle](https://www.kaggle.com/datasets/ianpetrustan/global-temperature-time-series)
