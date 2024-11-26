# AvocadoPricePred
Dataset
The dataset used for this project is the Avocado Prices dataset, available on Kaggle. It contains information about avocado prices across different regions of the United States from 2015 to 2018. The dataset includes the following features:

Date: The date of the avocado sale.
AveragePrice: The average price of an avocado.
Type: The type of avocado (organic or conventional).
Year: The year of the sale.
Region: The region where the avocado was sold.
Total Volume: The total number of avocados sold.
4046: The total number of avocados with PLU code 4046 (a specific variety of avocado).
4225: The total number of avocados with PLU code 4225 (another variety).
4770: The total number of avocados with PLU code 4770 (another variety).
Technologies Used
Python: The primary programming language.
Libraries:
pandas: Data manipulation and analysis.
numpy: Numerical operations.
matplotlib and seaborn: Data visualization.
scikit-learn: Machine learning models and evaluation.
xgboost: Gradient boosting machine for model training.
Jupyter Notebook: For exploratory data analysis and model development.
Project Steps
1. Data Preprocessing
Load the dataset and clean the data (e.g., handling missing values, converting date columns, etc.).
Perform feature engineering such as encoding categorical variables (e.g., region and type) and creating additional time-based features.
2. Data Exploration
Visualize trends in avocado prices over time and by region.
Perform correlation analysis to understand the relationships between features.
3. Model Development
Split the dataset into training and testing sets.
Train multiple models including:
Linear Regression
Decision Tree Regressor
Gradient Boosting Regressor
XGBoost Regressor
Use stacking (model ensembling) for improved performance.
4. Model Evaluation
Evaluate the models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2).
Choose the best-performing model based on test set results.
5. Model Interpretation and Prediction
Interpret the model’s predictions and identify key factors influencing avocado prices.
