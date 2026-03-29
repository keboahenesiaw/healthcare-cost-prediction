# Healthcare Cost Prediction Model

## Overview
This project builds a machine learning model to predict healthcare costs based on patient data such as age, BMI, smoking status, and region.

## Objective
To identify key drivers of healthcare costs and build a predictive model using linear regression.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Data Processing
- Loaded dataset using pandas
- Converted categorical variables into numerical form using one-hot encoding
- Split data into training and testing sets

## Model
- Used Linear Regression
- Trained on 80% of the data
- Tested on 20% of the data

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared (R²)

## Key Insights
- Smoking is the strongest predictor of healthcare costs
- BMI and age also significantly increase costs
- Region and gender have smaller effects

## Visualizations
- Actual vs Predicted scatter plot
- Boxplot showing the impact of smoking on healthcare costs

## Conclusion
The model successfully explains a large portion of healthcare cost variation and highlights key risk factors.

## Author
Kelvin Nana Boahene-Siaw
