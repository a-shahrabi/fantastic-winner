# Who was alive?


## Project Overview
This project uses machine learning to predict which passengers survived the Titanic shipwreck based on features like age, gender, ticket class, and more. It's my solution to the [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic), a popular entry-level machine learning challenge.

## The Challenge
The sinking of the Titanic in 1912 is one of history's most infamous shipwrecks. Of the 2,224 passengers and crew aboard, more than 1,500 died. This project aims to build a predictive model that answers the question: "what sorts of people were more likely to survive?" using passenger data (name, age, gender, socio-economic class, etc).

## Project Structure:

```
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
```


## Setup Instructions

### Prerequisites
- Python 3.8+
- Git

### Installation
1. Clone this repository
    ```
    git clone https://github.com/your-username/titanic-prediction.git
    cd titanic-prediction
    ```

2. Create a Python environment (optional but recommended)
    ```
    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    
    # For Windows
    python -m venv venv
    venv\Scripts\activate
    ```

3. Install dependencies
    ```
    pip install -r requirements.txt
    ```

4. Download the competition data from Kaggle and place it in the `data/` directory

## Data Description

### Features
- **PassengerId**: Unique identifier for each passenger
- **Survived**: Target variable (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Passenger name
- **Sex**: Passenger sex
- **Age**: Passenger age
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Approach

1. **Data Exploration**: Analyze the data to identify patterns and relationships
2. **Data Preprocessing**: Handle missing values and encode categorical features
3. **Feature Engineering**: Create new features that might help prediction
4. **Model Selection**: Compare various ML algorithms (Random Forest, Logistic Regression, etc.)
5. **Hyperparameter Tuning**: Optimize model parameters
6. **Evaluation**: Assess model performance using cross-validation
7. **Prediction**: Generate predictions for the test set

## Performance Metrics
The model's performance is evaluated using:
- Accuracy score
- ROC-AUC
- Confusion matrix

## Results
[To be updated as the project progresses]


## Future Improvements
- Ensemble multiple models
- Perform more feature engineering
- Try advanced algorithms like XGBoost or neural networks

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- The Kaggle community for their numerous tutorials and shared knowledge
- The Titanic competition for providing a great introductory challenge for machine learning
