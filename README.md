# Fitness Tracker – Calories Burned Prediction

## 📌 Project Overview

The **Fitness Tracker** project is a Machine Learning application that predicts the number of **calories burned** during physical activity based on various user attributes such as age, gender, height, weight, exercise duration, heart rate, and body temperature.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and performance evaluation.

---

## 🚀 Features

* Predicts calories burned during exercise
* Performs Exploratory Data Analysis (EDA)
* Detects missing values and duplicate records
* Feature selection and preprocessing
* Data visualization using graphs and charts
* Trains multiple Machine Learning models
* Hyperparameter tuning using GridSearchCV
* Compares model performance using evaluation metrics
* Generates accurate calorie predictions

---

## 📂 Dataset

The dataset contains information about users and their exercise sessions.

### Features

| Feature    | Description                       |
| ---------- | --------------------------------- |
| User_ID    | Unique identifier                 |
| Gender     | Male/Female                       |
| Age        | Age of the person                 |
| Height     | Height (cm)                       |
| Weight     | Weight (kg)                       |
| Duration   | Exercise duration (minutes)       |
| Heart_Rate | Heart rate during exercise        |
| Body_Temp  | Body temperature (°C)             |
| Calories   | Calories burned (Target Variable) |

---

## 🛠 Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Exploratory Data Analysis

The project performs:

* Dataset overview
* Statistical summary
* Missing value detection
* Duplicate value removal
* Feature distribution analysis
* Correlation analysis
* Box plots
* Histograms
* Heatmaps

---

## 🤖 Machine Learning Models

The notebook implements and compares the following regression models:

### 1. Linear Regression

* Baseline prediction model
* Simple and interpretable

### 2. Random Forest Regressor

* Ensemble learning algorithm
* Provides better prediction accuracy
* Hyperparameters optimized using GridSearchCV

---

## ⚙️ Machine Learning Pipeline

1. Import dataset
2. Data cleaning
3. Remove duplicates
4. Feature selection
5. Train-test split
6. Data preprocessing
7. Train Linear Regression
8. Train Random Forest Regressor
9. Evaluate models
10. Predict calories burned

---

## 📈 Evaluation Metrics

The models are evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

The Random Forest Regressor achieves better prediction accuracy than the Linear Regression model.
---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Fitness-Tracker.git
```

Navigate to the project folder

```bash
cd Fitness-Tracker
```

Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

Run the notebook

```bash
jupyter notebook fitness_tracker.ipynb
```

---

## 📌 Future Improvements

* Build a web application using Streamlit or Flask
* Deploy the model on the cloud
* Add BMI calculation
* Include personalized fitness recommendations
* Predict daily calorie requirements
* Integrate wearable device data
* Develop a mobile-friendly interface

---

## 💡 Learning Outcomes

This project demonstrates:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Regression algorithms
* Hyperparameter tuning
* Model evaluation
* Machine Learning workflow
* Predictive analytics

---

## 📷 Sample Workflow

```
User Inputs
     │
     ▼
Data Preprocessing
     │
     ▼
Feature Engineering
     │
     ▼
Machine Learning Model
     │
     ▼
Calories Burned Prediction
```

---

## 📚 Skills Demonstrated

* Python Programming
* Data Analysis
* Machine Learning
* Regression Models
* Random Forest
* Linear Regression
* Scikit-learn
* Data Visualization
* Feature Engineering
* Model Evaluation
* Hyperparameter Tuning
* Predictive Analytics

---


