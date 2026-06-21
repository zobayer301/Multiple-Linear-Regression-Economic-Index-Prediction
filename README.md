# Multiple-Linear-Regression-Economic-Index-Prediction
Predicting stock index prices using Multiple Linear Regression based on interest rates and unemployment rates.

This project demonstrates the implementation of Multiple Linear Regression using Python and Scikit-Learn to predict stock index prices based on economic indicators.

## Overview
The model uses:
- Interest Rate
- Unemployment Rate
to predict:
- Index Price
The project includes data preprocessing, visualization, correlation analysis, model training, and prediction.

## Dataset

Dataset file:
```
Economics.xlsx
```
### Features
| Feature | Description |
|-----------|------------|
| Interest_rate | Interest rate values |
| Unemployment_rate | Unemployment rate values |

### Target Variable
| Target |
|---------|
| Index_price |
Columns `Unnamed: 0`, `Year`, and `Month` are removed before training because they are not used in the model.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```
## Exploratory Data Analysis
The notebook performs:
- Pairplot visualization
- Correlation analysis
- Scatter plots
- Feature selection
- Train-test split

## Model
Multiple Linear Regression
Independent Variables:
```python
X = df_index[['Interest_rate', 'Unemployment_rate']]
```
Dependent Variable:
```python
y = df_index['Index_price']
```
Train-test split:
```python
test_size = 0.25
random_state = 42
```
## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Repository Structure

```
├── MultipleLinearRegression.ipynb
├── Economics.xlsx
├── README.md
└── requirements.txt
```
## Author
**Md. Zobayer Chowdhury**
- Computer Science and Engineering
- Interested in Data Science, Machine Learning, and Artificial Intelligence
