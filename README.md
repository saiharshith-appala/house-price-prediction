# House Price Prediction Using Machine Learning

## Project Overview

This project predicts house prices using Machine Learning algorithms based on various housing features. The model analyzes historical housing data and estimates the price of a house using attributes such as area, bedrooms, bathrooms, parking facilities, and other amenities.

The project demonstrates the complete Machine Learning workflow including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction.

---

## Features

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Correlation Heatmap
* Outlier Detection
* Feature Engineering
* Multiple Machine Learning Models
* Model Comparison
* Hyperparameter Tuning using GridSearchCV
* Cross Validation
* Learning Curve Analysis
* Residual Analysis
* Feature Importance Analysis
* Business Insights
* Model Saving and Loading using Pickle
* Custom House Price Prediction

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Pickle

---

## Machine Learning Models Used

### Linear Regression

Used as the baseline regression model.

### Decision Tree Regressor

Captures non-linear relationships between features and house prices.

### Random Forest Regressor

Ensemble learning algorithm that improves prediction accuracy.

### Gradient Boosting Regressor

Boosting-based algorithm that provides strong predictive performance.

---

## Dataset Features

| Feature          | Description                   |
| ---------------- | ----------------------------- |
| area             | Area of the house             |
| bedrooms         | Number of bedrooms            |
| bathrooms        | Number of bathrooms           |
| stories          | Number of floors              |
| parking          | Number of parking spaces      |
| mainroad         | Main road access              |
| guestroom        | Guest room availability       |
| basement         | Basement availability         |
| airconditioning  | Air conditioning availability |
| furnishingstatus | Furnishing status             |
| price            | Target variable               |

---

## Project Workflow

Dataset Collection
↓
Data Cleaning
↓
Exploratory Data Analysis
↓
Feature Engineering
↓
Train-Test Split
↓
Model Training
↓
Hyperparameter Tuning
↓
Cross Validation
↓
Model Evaluation
↓
House Price Prediction

---

## Exploratory Data Analysis

The project includes:

* House Price Distribution
* Correlation Heatmap
* Outlier Detection
* Pair Plot Analysis
* Learning Curve Visualization
* Residual Analysis

---

## Model Evaluation Metrics

The following evaluation metrics were used:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Feature Engineering

Additional features created:

* Room Density
* Bathroom Density
* Total Rooms

These engineered features help improve model performance.

---

## Model Saving

The trained model is saved using Pickle.

```python
pickle.dump(best_model, open("house_price_model.pkl", "wb"))
```

The saved model can be loaded later without retraining.

---

## Project Structure

house-price-prediction/

├── house_price_prediction.ipynb

├── Housing.csv

├── house_price_model.pkl

├── README.md

├── requirements.txt

└── images/

  ├── price_distribution.png

  ├── heatmap.png

  ├── pairplot.png

  ├── model_comparison.png

  ├── learning_curve.png

  ├── actual_vs_predicted.png

  ├── residual_analysis.png

  ├── error_distribution.png

  └── feature_importance.png

---

## Results

The project compares multiple regression algorithms and selects the best-performing model based on evaluation metrics and cross-validation scores.

The final model successfully predicts house prices with strong performance and provides insights into the most influential factors affecting property values.

---

## Future Enhancements

* Streamlit Web Application
* House Price Prediction Dashboard
* Real-Time Prediction Interface
* Location-Based Price Prediction
* Advanced Ensemble Models
* Cloud Deployment

---

## Conclusion

This project demonstrates an end-to-end Machine Learning pipeline for House Price Prediction. It covers data preprocessing, exploratory analysis, feature engineering, model selection, hyperparameter tuning, evaluation, and prediction. The project showcases practical Machine Learning skills and provides a strong foundation for real-world predictive analytics applications.
