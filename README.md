# Global-Temperature-Time-Series

### Overview

The Global Temperature Dataset Analysis project provides an in-depth exploration of historical temperature data to study long-term climate trends. By visualizing temperature changes over decades and analyzing their correlation with environmental factors like CO2 emissions or land use, this project highlights patterns critical for understanding climate change.

### Key Features

Data Cleaning:
- Handling missing temperature readings using interpolation.
- Identifying and addressing outliers caused by unusual weather events.
- Standardizing data formats for seamless analysis.

Data Transformation:
- Normalizing temperature values to account for changes in recording methods over time.

Visualization:
- Temperature trends across decades.
- Correlation matrix of temperature and other environmental factors.
- Distribution of normalized temperature values.

### Dataset Information

The dataset consists of temperature records for Earth's surface, collected from multiple sources. The data spans from 1880 to 2016, and it includes the following columns:

- Source: The dataset source (e.g., GCAG, GISTEMP).
- Date: The date the temperature was recorded.
- Mean: The average global temperature anomaly (in °C) for the given date.
- Year: The extracted year from the Date column.

#### Data Quality Concerns Addressed
- Missing Data: Missing values are interpolated based on surrounding data.
- Outliers: Extreme values are identified using statistical thresholds and flagged or removed.
- Normalization: Temperature values are scaled to a consistent range to allow fair comparisons across years.

### Expected Output

- Global Temperature Trend Plot: A line plot showing the global temperature trend from 1880 to 2016, highlighting key fluctuations over time.
- Correlation Heatmap: A heatmap showing correlations between the numerical columns, with a strong correlation (0.82) between the Year and Mean temperature.

#### Output

Visualizations:
- Global temperature trends over time.
- Correlation matrix of numeric variables.
- Histogram of normalized temperatures.

Cleaned Dataset:
- Saved as cleaned_temperature_data.csv in the project directory.

### Insights

- Correlation between Year and Mean Temperature: The dataset shows a strong positive correlation of 0.82 between the Year and the Mean temperature anomaly, indicating that the Earth's surface temperature has been steadily increasing over time.
- Visualizing Trends: The global temperature trend over time exhibits clear patterns of warming, especially in recent decades.

### Future Work

- Extended Analysis: Explore correlations with additional environmental factors such as CO2 emissions, sea level rise, or land use changes.
- Time Series Forecasting: Use time series models (ARIMA, LSTM, etc.) to predict future temperature trends based on historical data.
- Climate Change Modeling: Model the impact of various factors on global temperature and explore different climate change scenarios.

### Source

https://www.kaggle.com/datasets/ianpetrustan/global-temperature-time-series
