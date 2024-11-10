# Global-Temperature-Time-Series

### Overview

The goal of this project is to analyze historical global temperature data, visualize trends, and identify correlations between temperature and other factors. The dataset is ideal for practicing:

- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Data Visualization
- Correlation Analysis
- Time Series Analysis

### Dataset Information

The dataset consists of temperature records for Earth's surface, collected from multiple sources. The data spans from 1880 to 2016, and it includes the following columns:

- Source: The dataset source (e.g., GCAG, GISTEMP).
- Date: The date the temperature was recorded.
- Mean: The average global temperature anomaly (in °C) for the given date.
- Year: The extracted year from the Date column.

### Expected Output

- Global Temperature Trend Plot: A line plot showing the global temperature trend from 1880 to 2016, highlighting key fluctuations over time.
- Correlation Heatmap: A heatmap showing correlations between the numerical columns, with a strong correlation (0.82) between the Year and Mean temperature.

### Insights

- Correlation between Year and Mean Temperature: The dataset shows a strong positive correlation of 0.82 between the Year and the Mean temperature anomaly, indicating that the Earth's surface temperature has been steadily increasing over time.
- Visualizing Trends: The global temperature trend over time exhibits clear patterns of warming, especially in recent decades.

### Future Work

- Extended Analysis: Explore correlations with additional environmental factors such as CO2 emissions, sea level rise, or land use changes.
- Time Series Forecasting: Use time series models (ARIMA, LSTM, etc.) to predict future temperature trends based on historical data.
- Climate Change Modeling: Model the impact of various factors on global temperature and explore different climate change scenarios.

### Source

https://www.kaggle.com/datasets/ianpetrustan/global-temperature-time-series
