# Bus Passenger Demand Forecasting Using SARIMA

## Project Overview
This project focuses on analyzing historical bus passenger demand and forecasting future passenger demand using time-series forecasting techniques.

## Objectives
- Analyze daily passenger demand.
- Identify weekday and weekend demand patterns.
- Study monthly and yearly passenger trends.
- Analyze weekly seasonality.
- Perform stationarity testing and seasonal decomposition.
- Develop SARIMA forecasting models.
- Evaluate predictions using MAE and RMSE.

## Dataset
- Source: PublicTransportAI – Goiânia Public Transport Dataset
- Period: January 2013 – December 2016
- Total records: 1,461
- Frequency: Daily

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn

## Methodology
1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. ADF stationarity test
4. ACF and PACF analysis
5. Weekly seasonal decomposition
6. SARIMA model development
7. Passenger demand forecasting
8. Model evaluation and comparison

## Model Results

Selected baseline model: SARIMA(1,0,1)(1,0,1,7)

| Metric | Result |
|---|---:|
| MAE | 8,574.28 |
| RMSE | 11,262.10 |

Training period: January 2013 – May 2016

Testing period: June 2016

## Key Findings
- Weekly passenger demand seasonality was identified.
- Weekdays generally showed higher passenger demand than weekends.
- Working Days generally showed higher demand than Vacation periods.
- The baseline SARIMA model captured recurring weekly patterns.

## Limitations
- The dataset represents Goiânia, Brazil.
- Indian festival-specific information is not available in the dataset.
- Residual autocorrelation remains, and further model tuning is recommended.

## Future Improvements
- Further SARIMA parameter tuning.
- Additional model validation.
- Incorporating holiday and festival information when suitable data is available.
- Exploring additional forecasting techniques.

## Conclusion
This project demonstrates time-series analysis and SARIMA-based passenger demand forecasting using Python. It provides practical experience in data preprocessing, exploratory analysis, seasonality identification, forecasting and model evaluation.
