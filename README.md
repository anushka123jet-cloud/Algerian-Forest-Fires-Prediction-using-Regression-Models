# 🔥 Algerian Forest Fires Prediction using Machine Learning

## 📌 Project Overview

This project presents a complete end-to-end Machine Learning workflow on the Algerian Forest Fires Dataset. The objective is to analyze the factors influencing forest fires and build predictive regression models capable of estimating fire-related indices based on environmental and weather conditions.

The project covers every stage of a real-world Data Science pipeline, including data cleaning, exploratory data analysis (EDA), feature engineering, visualization, correlation analysis, model building, and performance evaluation.

---

## 🎯 Objectives

- Clean and preprocess raw data
- Perform Exploratory Data Analysis (EDA)
- Discover patterns and relationships among variables
- Engineer features for improved model performance
- Visualize trends using statistical plots
- Analyze feature correlations
- Train and evaluate multiple regression models
- Compare model performance using evaluation metrics

---

## 📂 Dataset Information

The Algerian Forest Fires Dataset contains meteorological and environmental attributes collected from different regions of Algeria.

### Features Include:
- Temperature
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rain
- Fine Fuel Moisture Code (FFMC)
- Duff Moisture Code (DMC)
- Drought Code (DC)
- Initial Spread Index (ISI)
- Fire Weather Index (FWI)
- Classes (Fire / Not Fire)

---

## ⚙️ Project Workflow

### 1️⃣ Data Cleaning & Preprocessing
- Handled missing values
- Removed inconsistencies
- Corrected data types
- Prepared data for analysis

### 2️⃣ Exploratory Data Analysis (EDA)
- Univariate Analysis
- Bivariate Analysis
- Distribution Analysis
- Outlier Detection

### 3️⃣ Feature Engineering
- Feature selection
- Data transformation
- Feature preparation for modeling

### 4️⃣ Data Visualization
Visualizations were created using:

- Matplotlib
- Seaborn

Plots include:
- Histograms
- Box Plots
- Scatter Plots
- Heatmaps
- Correlation Matrix
- Distribution Plots

### 5️⃣ Correlation Analysis
- Identified relationships among features
- Removed redundant information
- Improved model interpretability

### 6️⃣ Model Training

The following regression algorithms were implemented:

#### 📈 Linear Regression
Baseline regression model for prediction.

#### 📈 Ridge Regression
Regularized regression model to reduce overfitting.

#### 📈 Lasso Regression
Feature selection and regularization through L1 penalty.

---

## 📊 Model Evaluation

Models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

Performance comparison was conducted to determine the most effective regression model.

---

## 🛠️ Technologies Used

| Category | Tools |
|-----------|--------|
| Programming Language | Python |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| Development Environment | Jupyter Notebook |

---

## 📁 Project Structure
Algerian-Forest-Fires-Prediction/
│
├── Dataset/
│   ├── Algerian_forest_fires_dataset.csv
│   └── Algerian_forest_fires_cleaned.csv
│
├── Notebooks/
│   ├── Data_Cleaning_EDA.ipynb
│   └── Model_Training.ipynb
│
├── Models/
│   └── ridge_regression.pkl
│
├── README.md
└── requirements.txt


## 🚀 Key Outcomes

✔ Successfully cleaned and prepared real-world data

✔ Performed comprehensive Exploratory Data Analysis

✔ Identified important feature relationships through correlation analysis

✔ Built multiple regression models for prediction

✔ Compared model performances using standard evaluation metrics

✔ Developed a complete Machine Learning pipeline from raw data to prediction

---

## 💡 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Ensemble Learning Models
- Model Deployment using Flask/Streamlit
- Interactive Dashboard Development

---

## 👩‍💻 Author

### Anushka Verma MCA Student | Aspiring Data Scientist
MCA Student
Harcourt Butler Technical University (HBTU), Kanpur

---

⭐ If you found this project useful, consider giving it a star!
