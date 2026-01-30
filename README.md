# My First Machine Learning Model

## Overview
This is my first machine learning notebook, marking the beginning of my ML journey. I've previously worked with Jupyter Notebook and Google Colab, but this is my first time sharing my work publicly. This repository will be updated regularly as I progress through my machine learning coursework.

## Project Description
This notebook implements a **Decision Tree Regressor** to predict house prices using the Iowa Housing dataset. It's an exercise from Kaggle's [Introduction to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning) course.

## What I Learned
- Loading and exploring datasets with pandas
- Selecting target variables for prediction
- Creating feature sets from raw data
- Building and training a Decision Tree model using scikit-learn
- Making predictions with a trained model
- Understanding the basic ML workflow: data → model → predictions

## Dataset
**Iowa Housing Dataset** - Contains information about residential homes in Ames, Iowa, including features like:
- Lot area and configuration
- Year built and remodeled
- Number of bedrooms, bathrooms, and rooms
- Square footage of different floors
- Overall quality and condition ratings

**Target Variable:** `SalePrice` - The sale price of each house

## Features Used
The model uses the following features to predict house prices:
- `LotArea` - Lot size in square feet
- `YearBuilt` - Original construction date
- `1stFlrSF` - First floor square feet
- `2ndFlrSF` - Second floor square feet
- `FullBath` - Number of full bathrooms
- `BedroomAbvGr` - Number of bedrooms above ground
- `TotRmsAbvGrd` - Total rooms above ground

## Technologies Used
- **Python 3.11**
- **pandas** - Data manipulation and analysis
- **scikit-learn** - Machine learning model (DecisionTreeRegressor)
- **Kaggle Notebooks** - Development environment

## Key Code Snippets

### Loading the Data
```python
import pandas as pd
iowa_file_path = '../input/home-data-for-ml-course/train.csv'
home_data = pd.read_csv(iowa_file_path)
```

### Selecting Features and Target
```python
y = home_data.SalePrice
feature_names = ['LotArea', 'YearBuilt', '1stFlrSF', '2ndFlrSF', 
                 'FullBath', 'BedroomAbvGr', 'TotRmsAbvGrd']
X = home_data[feature_names]
```

### Building and Training the Model
```python
from sklearn.tree import DecisionTreeRegressor
iowa_model = DecisionTreeRegressor(random_state=1)
iowa_model.fit(X, y)
```

### Making Predictions
```python
predictions = iowa_model.predict(X)
```

## Results
The model successfully trains and makes predictions on the Iowa housing dataset. The predictions are stored in the `predictions` variable.

## What's Next
This is just the beginning! Next steps include:
- Model validation and evaluation
- Understanding metrics like MAE (Mean Absolute Error)
- Preventing overfitting
- Trying different models and comparing performance

## Course Progress
- [x] Your First Machine Learning Model
- [ ] Model Validation
- [ ] Underfitting and Overfitting
- [ ] Random Forests
- [ ] Exercise: Machine Learning Competitions

## How to Run
1. Visit the [Kaggle notebook](https://www.kaggle.com) (link to be added)
2. Fork the notebook to your account
3. Run all cells to reproduce the results

Or locally:
```bash
# Clone this repository
git clone https://github.com/YOUR_USERNAME/first-ml-model.git

# Install required packages
pip install pandas scikit-learn jupyter

# Open the notebook
jupyter notebook exercise-your-first-machine-learning-model.ipynb
```

## Acknowledgments
- Kaggle's [Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning) course
- Iowa Housing dataset provided by Kaggle

## Connect
I'm documenting my ML learning journey and will be posting more projects as I progress. Feel free to follow along!

---

*Last Updated: January 30, 2026*
