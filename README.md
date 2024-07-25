# Walmart-Sales-Forecast-EDA-and-Model-Building-RFR-and-ANN-
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
  Train and evaluate models using the scripts or notebooks provided. This project includes implementations of RandomForestRegressor and Artificial Neural Networks (ANN) for sales forecasting.
  
  - RandomForestRegressor:
  The RandomForestRegressor is an ensemble learning method that constructs multiple decision trees and merges them to get a more accurate and stable prediction. It is particularly effective for handling large datasets with numerous features and helps to reduce overfitting by averaging the results of many decision trees.
  
  - Artificial Neural Networks (ANN):
  ANNs are computational models inspired by the human brain, consisting of interconnected layers of neurons. They are capable of capturing complex patterns and relationships in the data. In this project, an ANN is trained to learn the nonlinear relationships between the input features and sales, providing robust predictions through backpropagation and optimization techniques.

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
