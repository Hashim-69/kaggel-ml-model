# My Machine Learning Journey

## Overview
This repository documents my machine learning learning journey, starting from my first model to more advanced concepts. I've previously worked with Jupyter Notebook and Google Colab, and I'm now publicly sharing my progress as I work through Kaggle's Introduction to Machine Learning course.

## Projects in This Repository

### 1. 📘 First Machine Learning Model
**File:** `exercise-your-first-machine-learning-model.ipynb`

My very first ML model! Built a **Decision Tree Regressor** to predict house prices.

**What I learned:**
- Loading and exploring datasets with pandas
- Selecting features and target variables
- Training a scikit-learn model
- Making predictions



---

### 2. 📊 Model Validation
**File:** `exercise-model-validation.ipynb`

Learned how to properly validate models and measure their accuracy.

**What I learned:**
- Train/test data splitting
- Why testing on training data is misleading
- Calculating Mean Absolute Error (MAE)
- Evaluating model performance on unseen data

**Results:** Achieved MAE of $29,652.93 on validation data

[View detailed README](./MODEL_VALIDATION_README.md)

---

## Dataset
**Iowa Housing Dataset** - Contains information about residential homes in Ames, Iowa

**Features used:**
- `LotArea` - Lot size in square feet
- `YearBuilt` - Original construction date
- `1stFlrSF` - First floor square feet
- `2ndFlrSF` - Second floor square feet
- `FullBath` - Number of full bathrooms
- `BedroomAbvGr` - Number of bedrooms above ground
- `TotRmsAbvGrd` - Total rooms above ground

**Target:** `SalePrice` - The sale price of each house

## Technologies Used
- **Python 3.11**
- **pandas** - Data manipulation and analysis
- **scikit-learn** - Machine learning models and validation
- **Kaggle Notebooks** - Development environment

## Course Progress
- [x] Your First Machine Learning Model
- [x] Model Validation
- [ ] Underfitting and Overfitting
- [ ] Random Forests
- [ ] Exercise: Machine Learning Competitions

## Key Learnings So Far

### From First Model:
✅ How to load and prepare data
✅ Building a Decision Tree model
✅ Making predictions with trained models

### From Model Validation:
✅ The importance of train/test splits
✅ Why in-sample predictions can be misleading
✅ How to measure model accuracy with MAE
✅ Proper model evaluation techniques

## What's Next
- Understanding overfitting and underfitting
- Learning to optimize model parameters
- Trying different algorithms (Random Forests)
- Competing in Kaggle competitions

## Installation & Setup

```bash
# Clone this repository
git clone https://github.com/Hashim-69/kaggel-ml-model.git

# Install required packages
pip install -r requirements.txt

# Open notebooks
jupyter notebook
```

## Repository Structure
```
kaggel-ml-model/
├── exercise-your-first-machine-learning-model.ipynb
├── exercise-model-validation.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Credits 
- Kaggle's [Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning) course
- Iowa Housing dataset provided by Kaggle

## Connect
Following my ML learning journey from zero to job-ready! More projects are coming as I progress through the course.

---

*Repository started: January 30, 2026*  
*Last Updated: January 31, 2026*
