# California Housing Price Prediction using Machine Learning

## Project Overview

This project develops an end-to-end Machine Learning pipeline to predict housing prices using the California Housing dataset. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and performance evaluation.

The goal is to build an accurate regression model capable of estimating house prices based on various housing and demographic features.

---

## Problem Statement

Accurately predicting house prices is important for buyers, sellers, real estate agencies, and investors. This project uses machine learning techniques to analyze housing-related factors and estimate property values.

---

## Dataset

- Dataset: California Housing Dataset
- Source: Scikit-Learn Built-in Dataset
- Target Variable: Median House Value

### Features

- MedInc (Median Income)
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Project Workflow

### 1. Data Loading
- Imported California Housing dataset
- Converted dataset into Pandas DataFrame

### 2. Exploratory Data Analysis (EDA)
- Statistical summary
- Missing value analysis
- Feature distribution analysis
- Correlation analysis
- Data visualization

### 3. Data Preprocessing
- Missing value handling
- Feature scaling
- Pipeline creation
- Train-test split

### 4. Model Development
Implemented and compared multiple regression models:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

### 5. Hyperparameter Tuning
- GridSearchCV
- Cross Validation
- Model optimization

### 6. Model Evaluation

Evaluation metrics used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Results

The best-performing model was selected based on:

- Lowest RMSE
- Lowest MAE
- Highest R² Score

The final model demonstrates strong predictive performance on unseen housing data.

---

## Key Features

✔ End-to-End Machine Learning Workflow

✔ Exploratory Data Analysis (EDA)

✔ Feature Engineering & Preprocessing

✔ Cross Validation

✔ Hyperparameter Tuning using GridSearchCV

✔ Performance Evaluation using Multiple Metrics

✔ Real-Time House Price Prediction

---

## Project Structure

```
California-Housing-Prediction/
│
├── House_Price_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/california-housing-price-prediction.git
```

Move into the project directory:

```bash
cd california-housing-price-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```bash
House_Price_Prediction.ipynb
```

---

## Future Improvements

- Deploy model using Flask/FastAPI
- Create interactive web application
- Integrate real-world housing datasets
- Add model monitoring and tracking

---

## Author

Nikhil Vishwakarma

Data Analytics | Machine Learning | SQL | Python | Tableau | Power BI
