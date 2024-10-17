# House Price Prediction Project
This project is part of the AAI-500-01 course in the Applied Artificial Intelligence Program at the University of San Diego (USD).

**-- Project Status: Completed**

### Installation

To run this project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/apadin-usd/AAI-500-Final-Project-Code-Team-4```
2. Run with Jypiter: https://jupyter.org/install 

## Project Intro/Objective
The main objective of this project is to build a predictive model that can accurately estimate house prices based on various property features such as area, number of bedrooms, bathrooms, amenities, and other characteristics. The model will help predict house prices and provide insights into the key factors that influence pricing in the real estate market.

### Contributors
- Alexander J Padin
- Juan Pablo Triana Martinez
- Marquise Oliver

### Methods Used
- Exploratory Data Analysis (EDA)
- Data Cleaning and Preparation
- Inferential Statistics
- Linear Regression (OLS)
- Lasso Regression
- Ridge Regression
- GLM Gamma Regression
- Model Evaluation
- Data Visualization

### Technologies
- Python
- Jupyter Notebook

## Project Description

#### Dataset
- **Source**: https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction
- **Variables**: The dataset includes features such as `area`, `bedrooms`, `bathrooms`, `airconditioning`, `furnishingstatus`, and `price` (target variable).
- **Size**: The dataset contains *545*  rows and *13* columns.

The dataset was cleaned by handling missing values and encoding categorical variables. The target variable (house prices) is right-skewed, making it an ideal candidate for models that handle skewed distributions, such as **Gamma Regression**. However, after analysing performance, we concluded that **Ordinary Least Squares (OLS)** model was a better fit to predict house prices.

#### Models: Used
- **Ordinary Least Squares (OLS)**: This is the baseline model used for interpreting linear relationships between house prices and independent variables.
- **Lasso Regression**: Used for automatic feature selection by shrinking irrelevant coefficients to zero.
- **GLM Gamma**: Used to model skewed data, which is common in housing prices, as it assumes a Gamma distribution for the target variable.

#### Project Steps:
1. **Data Cleaning/Preparation**: Missing values were handled, categorical features were encoded.
2. **Exploratory Data Analysis**: The data was visualized using correlation matrices, scatter plots, and distribution plots to explore relationships between features and house prices.
3. **Model Selection**: Various regression models were explored to find the best fit for the dataset.
4. **Model Analysis**: The models were evaluated based on R-squared, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). OLS emerged as the most interpretable and effective model.
5. **Conclusion & Recommendations**: OLS is recommended as the best model for this dataset, with the possibility of improving future performance by adding external data (e.g., proximity to schools, crime rates).

#### License
This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.


