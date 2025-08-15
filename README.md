#  Housing Price Prediction Model

A machine learning model that predicts housing prices based on various property and location features.  
The project uses a dataset sourced from Kaggle and is implemented in Python with popular data science libraries.

---

## Project Overview
Housing prices are influenced by multiple factors such as location, size, condition, and neighborhood characteristics.  
This project applies supervised machine learning techniques to predict the price of a house given its attributes.  
Such a model can help real estate professionals, property buyers, and investors make data-driven decisions.

---

##  Dataset
- **Source:** [Kaggle Housing Prices Dataset]
- **Content:** Includes features such as:
  - Lot area
  - Number of bedrooms and bathrooms
  - Square footage of living area
  - Neighborhood
  - Quality and condition ratings
  - Other property characteristics
- **Target Variable:** `SalePrice` (continuous numerical value)

---

## Tech Stack & Tools
- **Programming Language:** Python  
- **Libraries & Packages:**
  - `pandas` → Data manipulation
  - `numpy` → Numerical computations
  - `scikit-learn` → Model training and evaluation
  - `matplotlib` / `seaborn` → Data visualization
  - `jupyter notebook` → Development environment

---

## Methodology
1. **Data Collection:** Downloaded dataset from Kaggle.
2. **Data Preprocessing:**
   - Handling missing values
   - Encoding categorical features
   - Scaling numerical features
3. **Exploratory Data Analysis (EDA):**
   - Visualizing feature distributions
   - Correlation heatmaps
   - Outlier detection
4. **Model Training:**
   - Tried multiple regression algorithms:
     - Linear Regression
     - Random Forest Regressor
     - Gradient Boosting Regressor
   - Used cross-validation to compare models
5. **Model Evaluation Metrics:**
   - R² score
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
6. **Best Model Selection:** Chose the model with the lowest RMSE on validation data.
