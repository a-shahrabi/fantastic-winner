# Who was alive?


## Project Overview
This project uses machine learning to predict which passengers survived the Titanic shipwreck based on features like age, gender, ticket class, and more. It's my solution to the [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic), a popular entry-level machine learning challenge.

## The Challenge
The sinking of the Titanic in 1912 is one of history's most infamous shipwrecks. Of the 2,224 passengers and crew aboard, more than 1,500 died. This project aims to build a predictive model that answers the question: "what sorts of people were more likely to survive?" using passenger data (name, age, gender, socio-economic class, etc).

## Project Structure:

titanic-prediction/
│
├── data/                  # Competition data files
│   ├── train.csv          # Training data with survival information
│   └── test.csv           # Test data for making predictions
│
├── notebooks/             # Jupyter notebooks
│   ├── exploratory_analysis.ipynb    # Data exploration and visualization
│   └── model_development.ipynb       # Model training and evaluation
│
├── src/                   # Source code
│   ├── preprocessing.py   # Data preprocessing functions
│   ├── features.py        # Feature engineering
│   └── model.py           # Model training and evaluation
│
├── requirements.txt       # Required Python packages
├── README.md              # Project documentation
└── .gitignore             # Specifies intentionally untracked files
