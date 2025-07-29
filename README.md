# Weather_Prediction_Project
# 🌦️ Weather Condition Prediction using Machine Learning

## 📌 Overview

This project is aimed at predicting **weather conditions** (like Sunny, Rainy, Cloudy, etc.) using **Supervised Machine Learning models** based on historical weather data. It includes steps like data preprocessing, exploratory data analysis (EDA), model building, evaluation, and performance visualization.

---

## 👥 Team Members

- 👤 Member 1: [Piyush Mishra] – Machine Learning Model Development  
- 👤 Member 2: [Shubham] – Data Cleaning & Preprocessing  
- 👤 Member 3: [Hariom Pathak] – Data Visualization & EDA  

---

## 📁 Project Structure

weather-prediction/
│
├── data/
│ └── weather_data.csv # Raw Dataset
│
├── notebooks/
│ ├── 1_data_cleaning.ipynb # Data Cleaning steps
│ ├── 2_visualization_eda.ipynb # EDA & Graphs
│ └── 3_ml_model.ipynb # ML Model training and evaluation
│
├── images/
│ └── confusion_matrix.png # Evaluation graphs & plots
│
├── README.md # Project documentation
├── requirements.txt # Python libraries used
└── weather_prediction.pptx # Final presentation



---

## 📊 Dataset Info

- 📁 **Source**: Kaggle  
- 📌 **Features Used**:
  - Temperature
  - Humidity
  - Pressure
  - Wind Speed
  - Dew Point
  - Weather Condition (Target)

---

## 🧹 Data Cleaning

- Removed missing/null values
- Handled incorrect entries
- Converted categorical labels (Label Encoding if used)
- Ensured all features are in correct data types

---

## 📈 Exploratory Data Analysis

- Correlation matrix to understand feature relationships
- Bar plots, histograms, and line graphs for data visualization
- Distribution of weather conditions

---

## 🤖 Machine Learning Models Used

- ✅ **Logistic Regression**
- ✅ **Random Forest Classifier**

📌 **Best Model**: Random Forest achieved the highest accuracy on test data.

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

📌 **Model Accuracy**: `~54.75%` with Random Forest (verify if not overfitting)

---

## ⚙️ Requirements

pandas
numpy
matplotlib
seaborn
scikit-learn



Install using:

```bash
pip install -r requirements.txt



🚀 How to Run
Clone the repository

Open notebooks in order:

1_data_cleaning.ipynb

2_visualization_eda.ipynb

3_ml_model.ipynb





