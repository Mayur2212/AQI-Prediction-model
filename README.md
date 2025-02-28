# AQI-Prediction-model
This project predicts the Air Quality Index (AQI) using machine learning. It involves data preprocessing, handling missing values, feature selection, and training a `RandomForestRegressor` model. The model is evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) score.
# Air Quality Index Prediction

## Project Overview
This project aims to predict the Air Quality Index (AQI) using machine learning. It leverages a dataset containing air quality parameters to train a predictive model. The implementation includes data preprocessing, feature selection, model training, evaluation, and visualization.

## Dataset
- The dataset is stored in `air quality data.csv`.
- It contains air quality parameters such as pollutant concentrations and meteorological features.
- The target variable is `AQI` (Air Quality Index).

## Technologies Used
- Python
- Pandas, NumPy (Data Manipulation)
- Matplotlib, Seaborn (Visualization)
- Scikit-Learn (Machine Learning)

## Steps Involved
1. Load and explore the dataset.
2. Handle missing values.
3. Perform feature selection and scaling.
4. Split the data into training and testing sets.
5. Train a `RandomForestRegressor` model.
6. Evaluate the model using MAE, MSE, and R² score.
7. Visualize the actual vs predicted AQI values.

## Installation
To run this project, install the required dependencies:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Place `air quality data.csv` in the project directory.
2. Run the Jupyter Notebook or Python script.
3. View model performance metrics and visualization.

## Output
- The model provides AQI predictions based on input features.
- Displays error metrics: MAE, MSE, R² score.
- Scatter plot comparing actual vs predicted AQI values.

## Contributing
Feel free to contribute by improving data processing, experimenting with different models, or enhancing visualizations.

## License
This project is open-source and available under the MIT License.

