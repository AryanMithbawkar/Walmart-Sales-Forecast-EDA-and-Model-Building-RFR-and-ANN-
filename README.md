# Walmart-Sales-Forecast-EDA-and-Model-Building-And-Testing
This repository contains code and data for Walmart Sales Forecasting. It includes data acquisition, preprocessing, and visualization. Use the provided notebooks and scripts for exploratory data analysis, model training, and testing. Key datasets: features.csv, stores.csv, train.csv. Visualizations highlight trends and relationships in sales data.

# Walmart Sales Forecast
This repository contains the code and data used for analyzing and forecasting sales for Walmart stores. The project involves data acquisition, preprocessing, and visualization to provide insights into the factors affecting sales performance.

## Data
The following datasets are used in this project:

+ features.csv: Contains information on store features such as temperature, fuel price, CPI, and unemployment.
+ stores.csv: Contains information on store types and sizes.
+ train.csv: Contains the historical sales data for various departments within each store.

## Project Structure
+ data/: Directory containing the datasets.
+ notebooks/: Jupyter notebooks used for data analysis and visualization.
+ scripts/: Python scripts for data preprocessing and analysis.
+ README.md: Project overview and instructions.

## Installation
1. Clone the repository:
  ```
  git clone https://github.com/AryanMithbawkar/walmart-sales-forecast.git
  ```
2. Navigate to the project directory:
```
cd walmart-sales-forecast
```
3. Install the required packages:
```
pip install -r requirements.txt
```
## Usage
1. Data Preprocessing: The script scripts/preprocess_data.py handles merging datasets and cleaning the data.
```
python scripts/preprocess_data.py
```
2. Exploratory Data Analysis: Use the notebooks in the notebooks/ directory to explore the data and generate visualizations.
```
jupyter notebook notebooks/exploratory_analysis.ipynb
```
3. Model Training and Evaluation: Train and evaluate models using the scripts or notebooks provided.
   
+ Model Training and Evaluation
  Train and evaluate models using the scripts or notebooks provided. This project includes implementations of RandomForestRegressor, Linear Regression, Polynomial Regression, Ridge, and Lasso for sales forecasting.
  
  - RandomForestRegressor: An ensemble method that uses multiple decision trees to improve prediction accuracy and control over-fitting.
  - Linear Regression: A basic predictive analysis technique that shows the relationship between two variables by fitting a linear equation.
  - Polynomial Regression: Extends linear regression by considering polynomial features, allowing it to model nonlinear relationships.
  - Ridge Regression: Ridge Regression (also known as Tikhonov regularization) is a technique used to analyze multiple regression data that suffer from multicollinearity. It adds a penalty on the size of coefficients to prevent overfitting.
  - Lasso Regression: Lasso Regression (Least Absolute Shrinkage and Selection Operator) is similar to Ridge Regression but includes a penalty term that can drive some coefficients to zero. This makes it useful for feature selection in high-dimensional datasets.
  
 
## Visualization
The project includes various plots for data exploration and analysis:

+ Pairplots to examine relationships between features.
+ Correlation heatmaps to identify highly correlated features.
+ Boxplots and bar plots for categorical and numerical data distributions.
+ Line plots for trends over time.

## Contributing
1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
This project uses data provided by Walmart and follows the structure and guidelines as per the requirements of the Walmart Sales Forecast competition.
