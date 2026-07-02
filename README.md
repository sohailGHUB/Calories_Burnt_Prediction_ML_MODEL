# Calories_Burnt_Prediction_ML_MODEL
# Calories Burnt Prediction System

## Overview

This project predicts the number of calories burned during physical activities using Machine Learning regression techniques. The model is trained on physiological and activity-related features to estimate calorie expenditure accurately.

## Features

- Data preprocessing and cleaning using Pandas
- Feature engineering and exploratory data analysis
- Machine Learning regression models
- Model evaluation using standard regression metrics
- Calorie prediction for new input data

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Google Colab

## Project Structure

```
Calories-Burnt-Prediction/
│
├── Calories_Burnt_Prediction.ipynb
├── README.md
├── requirements.txt
├── dataset.csv
└── images/
    ├── model_results.png
    └── feature_importance.png
```

## Dataset

The dataset contains physiological and activity-related attributes such as:

- Gender
- Age
- Height
- Weight
- Duration
- Heart Rate
- Body Temperature
- Calories Burned

## Machine Learning Workflow

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Prediction

## Algorithms Used

- Linear Regression
- Gradient Boosting Regressor
- XGBoost Regressor

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

## Results

Among the evaluated models, XGBoost Regression achieved the best prediction performance and outperformed the baseline regression models.

## How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Calories-Burnt-Prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook Calories_Burnt_Prediction.ipynb
```

or upload the notebook to Google Colab.

## Future Improvements

- Hyperparameter tuning
- Model deployment using Flask/FastAPI
- Streamlit web application
- Real-time calorie prediction interface

## Author

**Mohd Sohail Akhter**

LinkedIn: https://linkedin.com/in/sohail-akhter

GitHub: https://github.com/sohailGHUB
