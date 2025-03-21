# Medical Cost Prediction

## Overview
This project predicts medical insurance charges using **Multiple Linear Regression** and other regression techniques.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Statsmodels
- **Machine Learning Models:** Linear Regression, Ridge Regression, Lasso Regression, Polynomial Regression
- **Data Processing:** One-Hot Encoding, Variance Inflation Factor (VIF), Outlier Detection

## Dataset Details
- **Dataset Name:** Medical Cost Personal Dataset
- **Features:** Age, Sex, BMI, Children, Smoker, Region, Charges
- **Objective:** Predict **insurance charges** based on independent variables.

## Steps to Implement
### 1. Dataset Exploration
- Load dataset using `pandas`
- Check for missing values and data types
- Perform **Exploratory Data Analysis (EDA)** using scatter plots and correlation heatmaps

### 2. Data Preprocessing
- Handle missing values (if any)
- Convert categorical variables (**Sex, Smoker, Region**) using **One-Hot Encoding**
- Identify outliers using **box plots**
- Perform feature selection
- Split dataset into **80% training** and **20% testing** sets

### 3. Model Implementation
- Train a **Multiple Linear Regression** model
- Extract and analyze model coefficients and intercept

### 4. Model Evaluation
- Predict insurance charges on the test set
- Evaluate model performance using:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
  - **R² Score (Coefficient of Determination)**
- Visualize **Actual vs Predicted Charges**

### 5. Advanced Analysis (Optional)
- **Feature Importance:** Identify key predictors of insurance charges
- **Multicollinearity Check:** Use **Variance Inflation Factor (VIF)** to detect correlation
- **Compare with Ridge, Lasso, and Polynomial Regression**

## Installation & Usage
```bash
# Clone the repository
git clone https://github.com/your-username/medical-cost-prediction.git

# Navigate to the project directory
cd medical-cost-prediction

# Install dependencies
pip install -r requirements.txt

# Run the script
python medical_cost_prediction.py
```

## Contributors
- **Lokesh Veeramalla**  
- Contact: [lokeshveeramalla7@gmail.com](mailto:lokeshveeramalla7@gmail.com)



