# Chennai Housing Price Prediction

## Overview
This project focuses on predicting housing prices in Chennai using a dataset containing information on house features such as size, number of bedrooms, location, and amenities. The goal is to develop a machine learning model that accurately estimates house prices, aiding buyers, sellers, and real estate analysts in making data-driven decisions.

---

## Dataset Information
The dataset used in this project contains housing data scraped from metropolitan areas of Chennai. It includes the following columns:
- **Price**: Target variable representing the price of the house.
- **Area**: Size of the house in square feet.
- **No. of Bedrooms**: Number of bedrooms in the house.
- **Amenities**: Availability of amenities like swimming pool, gymnasium, clubhouse, and more.

### Key Highlights:
- Includes numerical and categorical features.
- Missing values are marked as `9` in the dataset.
- Multiple features with varying importance for predicting house prices.

---

## Project Structure
The repository contains the following files and directories:


---

## Key Steps in the Project
### 1. Data Cleaning and Preprocessing
- Handled missing values for both numerical and categorical features.
- Dropped irrelevant or redundant columns.
- Encoded categorical variables using Label Encoding.

### 2. Exploratory Data Analysis (EDA)
- Analyzed data distributions and relationships.
- Visualized key features using correlation heatmaps and boxplots.
- Identified and handled outliers for better model performance.

### 3. Feature Engineering
- Normalized numerical features using `StandardScaler`.
- Selected important features using Random Forest feature importance analysis.

### 4. Model Development
- Built a **Random Forest Regressor** for predicting house prices.
- Evaluated the model using **RMSE**, **MAE**, and **R²** metrics.

### 5. Hyperparameter Tuning
- Performed Grid Search to find the optimal parameters for the Random Forest model.

### 6. Model Deployment
- Saved the trained model using `joblib` for future predictions.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Data manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine learning: `sklearn`
  - Model persistence: `joblib`

