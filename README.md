# Predicting Airbnb Prices Using Multiple Linear Regression 🏡

This project predicts Airbnb listing prices using a Multiple Linear Regression model. The project demonstrates a complete data science workflow including data cleaning, exploratory data analysis, feature engineering, model building, evaluation, and interpretation of results.

---

# Objectives

- Build a multiple linear regression model to predict Airbnb listing prices
- Clean and preprocess Airbnb listing data
- Analyze relationships between listing features and price
- Evaluate model performance using regression metrics
- Identify the variables that most influence Airbnb prices
- Communicate findings through visualizations and interpretation

---

# Dataset

The dataset contains Airbnb listing information including features such as:

- Location
- Property type
- Room type
- Number of bedrooms
- Reviews
- Availability
- Booking information
- Price

The final dataset used for modeling contained over 74,000 Airbnb listings after cleaning and preprocessing.

---

# Tools and Libraries

- Python (`pandas`, `numpy`)
- scikit-learn (`LinearRegression`, `train_test_split`, `metrics`)
- matplotlib
- seaborn
- Jupyter Notebook

---

# Workflow

## 1. Data Cleaning and Preprocessing

- Removed unnecessary columns
- Handled missing values
- Encoded categorical variables
- Converted variables into appropriate formats
- Split the dataset into training and testing sets

## 2. Exploratory Data Analysis

- Examined distributions of Airbnb prices
- Analyzed relationships between predictors and price
- Identified trends and possible outliers
- Visualized important variables

## 3. Model Building

- Built a Multiple Linear Regression model
- Trained the model using the training dataset
- Predicted Airbnb log prices using listing characteristics

## 4. Model Evaluation

The model was evaluated using:

- R-squared
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## 5. Interpretation of Results

- Determined which features had the strongest relationship with Airbnb prices
- Compared predicted prices to actual prices
- Evaluated the overall predictive ability of the model

## Residual Distribution


The histogram below shows the distribution of residuals from the regression model.

![Residual Distribution](residual_distribution.png)

---

# Results


- The regression model explained approximately **58%** of the variation in Airbnb prices.
- Features such as location, property type, room type, number of bedrooms, and reviews had meaningful impacts on pricing.
- The model demonstrated moderate predictive ability and showed that listing characteristics play a significant role in determining Airbnb prices.

The findings suggest that machine learning and regression techniques can be useful tools for understanding and predicting Airbnb market pricing trends.

---

# Repository Structure

```bash
Airbnb_price_model/
│
├── Airbnb_price_model.ipynb     # Main Jupyter Notebook
├── Airbnb_Data.csv              # Dataset used for analysis
├── README.md                    # Project overview
