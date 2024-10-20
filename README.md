# Weather Classification Project

## Overview
This project aims to classify weather conditions using a dataset that includes various meteorological features. The dataset consists of 13,200 samples with the following columns:

- **Temperature**: Float, the temperature in degrees.
- **Humidity**: Integer, percentage of humidity.
- **Wind Speed**: Float, speed of the wind.
- **Precipitation (%)**: Float, percentage of precipitation.
- **Cloud Cover**: Categorical, description of cloud coverage.
- **Atmospheric Pressure**: Float, pressure in hPa.
- **UV Index**: Integer, level of UV radiation.
- **Season**: Categorical, seasonal classification.
- **Visibility (km)**: Float, visibility in kilometers.
- **Location**: Categorical, location of the weather observation.
- **Weather Type**: Categorical, classification of weather condition.

## Project Structure
1. **Library Imports**: Essential libraries for data manipulation, visualization, and machine learning are imported.
2. **Data Cleaning**: The dataset is cleaned to ensure quality and consistency.
3. **Exploratory Data Analysis (EDA)**:
   - Visualizations (histograms, scatter plots, box plots) for numerical features.
   - Count plots for categorical features.
   - Correlation analysis.
   - Seasonal weather patterns analysis.
4. **Data Processing**:
   - Feature engineering.
   - Scaling and normalization of numerical features.
   - Splitting the dataset into training and testing sets.
5. **Machine Learning**:
   - Model selection and training.
   - Evaluation of model performance.
   - Hyperparameter tuning.
   - Final model evaluation.
6. **Feature Importance**:
   - Extract feature importances.
   - Create a DataFrame for better visualization.
   - Sort and print feature importances.
   - Visualize importance using a bar plot.
7. **Conclusion**: Summary of findings.

## Code and Data Files
- The main code can be found in the Jupyter Notebook file: **`weather_project.ipynb`**.
- The dataset is located in: **`weather_classification_data.csv`**.

## Usage
To run the project, ensure that the required libraries are installed and execute the Jupyter Notebook. Analyze the visualizations and model results to gain insights into weather classification.

---

For any inquiries or further information, please contact the project author.
