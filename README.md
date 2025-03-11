# Demand Forecasting using Time-Series and Machine Learning

## Project Description
This project develops a demand forecasting model using time-series analysis and machine learning techniques to optimize inventory planning and sales strategy. The model is trained on Walmart's historical sales data, incorporating external factors such as seasonality, promotions, fuel prices, and economic indicators. 

The project uses:
- **Time-Series Models:** ARIMA, SARIMA, and Prophet for forecasting demand fluctuations.
- **Machine Learning:** Random Forest for demand prediction.
- **Power BI Dashboards:** To visualize insights for data-driven decision-making.

## Dataset
The dataset consists of four files:
- `features.csv`: Store-level attributes including temperature, fuel price, markdowns, CPI, and unemployment.
- `stores.csv`: Store details including store type and size.
- `train.csv`: Historical weekly sales for stores and departments.
- `test.csv`: Test dataset for making predictions.

## Installation
To set up the project environment, install the required dependencies:

```sh
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn prophet
```

Ensure that the dataset files (`features.csv`, `stores.csv`, `train.csv`, `test.csv`) are placed in the appropriate directory.

## Usage
Run the Jupyter Notebook `Demand Forecasting.ipynb` to:
1. Load and preprocess data.
2. Perform exploratory data analysis (EDA).
3. Train time-series forecasting models (SARIMA, Prophet).
4. Train a machine learning model (Random Forest) for sales prediction.
5. Evaluate models using MAE and MSE.
6. Predict future sales for the test dataset.

## Model Evaluation
- **SARIMA & Prophet:** Used for time-series forecasting.
- **Random Forest:** Used for machine learning-based predictions.
- **Evaluation Metrics:** Mean Absolute Error (MAE) and Mean Squared Error (MSE) used to compare models.

## Visualization
Power BI dashboards are designed to visualize insights such as:
- Historical sales trends
- Forecasted sales
- Impact of external factors on demand

## Results & Findings
- Incorporating external factors improved forecast accuracy.
- Machine learning outperformed traditional time-series models in capturing demand fluctuations.
- Seasonal trends significantly influenced demand patterns.

## Future Improvements
- Experiment with deep learning models (LSTMs, Transformers) for better accuracy.
- Incorporate additional economic indicators for improved predictions.
- Deploy the model as an API for real-time forecasting.

## Author
**Bhavya Sharma**

## License
This project is licensed under the MIT License.

