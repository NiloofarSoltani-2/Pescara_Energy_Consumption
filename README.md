# Fater Project - Electricity Consumption Forecasting

## Overview
The **Fater Project** aims to develop a long-term forecasting model to predict monthly electricity consumption at the **Fater Pescara plant** over a 12-month period. The project leverages time series analysis techniques, specifically the **ARIMA model**, to optimize budget allocation for energy consumption and improve company investments.

## Project Goals
- Analyze electricity consumption data from multiple production lines.
- Develop an accurate forecasting model for monthly energy consumption.
- Identify key factors influencing electricity usage.
- Support decision-making for energy budget optimization at Fater.

## Datasets
The project utilizes two datasets:

### 1. **df_msu (Production Data)**
This dataset contains production-related metrics, including:

| Column | Description |
|--------|-------------|
| **group** | Production group |
| **line** | Production line name |
| **product_code** | Final product code |
| **production_date** | Date of production |
| **good_theoretical_products_percent** | Percentage of good products vs theoretical maximum |
| **discard_product_percent** | Percentage of discarded products |
| **good_products** | Count of good products produced |
| **total_products** | Total number of products |
| **discarded_products** | Count of discarded products |
| **uma_total_products** | Total products in MSU |
| **uma_discarded_products** | Discarded products in MSU |
| **uma_good_products** | Good products in MSU |
| **time_can_online_percent** | Percentage of time the production line was online |
| **time_online** | Total time the line was operational |
| **line_efficiency** | Efficiency of the production line |
| **designed_efficiency** | Designed efficiency of the production line |

### 2. **df_consumption (Electricity Consumption Data)**
This dataset contains information about electricity usage for different production lines and utilities at the Fater Pescara plant. It is used to model and forecast energy consumption trends.

## Methodology

### 1. **Data Preprocessing**
- Cleaning and transforming data.
- Handling missing values and outliers.
- Merging production and consumption datasets.

### 2. **Exploratory Data Analysis (EDA)**
- Understanding consumption trends and correlations.
- Identifying seasonality and patterns in electricity usage.

### 3. **Time Series Forecasting**
- Implementing **ARIMA** for long-term forecasting.
- Evaluating model performance using appropriate metrics.

### 4. **Visualization & Reporting**
- Presenting findings with data visualizations.
- Generating insights for decision-making.

## Tools & Technologies
- **Python** (`pandas`, `NumPy`, `scikit-learn`, `statsmodels`)
- **Time Series Analysis** (`ARIMA` modeling)
- **Data Visualization** (`Matplotlib`, `Seaborn`)
- **Databricks & Spark** (for handling large-scale data)

## Expected Outcomes
- A reliable forecasting model for electricity consumption.
- Insights into energy usage patterns.
- Recommendations for optimizing electricity costs at Fater.

## How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/fater-project.git
1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt

1. **Run the preprocessing script:**
   ```bash
   python preprocess.py

1. **Train the ARIMA model:**
   ```bash
   python train_model.py

1. **Generate forecasts and visualize results:**
   ```bash
   python forecast.py


Contributors
**Niloofar Soltani** - Data Science & Machine Learning
Team Members - Raha and Mohadesse
