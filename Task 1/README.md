# Titanic Survival Prediction

This project focuses on building a machine learning model to predict the survival of passengers on the Titanic using the famous Titanic dataset.

## Dataset

The dataset used contains information about individual passengers, such as:
- **PassengerId**: Unique ID for each passenger
- **Survived**: Survival (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Passenger's name
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Structure

```
├── Titanic-Dataset.csv
├── titanic_survival_prediction.py
└── README.md
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-survival-prediction.git
   cd titanic-survival-prediction
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

## Usage

Run the Python script to train and evaluate the model:
```bash
python titanic_survival_prediction.py
```

## Features
- **Data Cleaning & Preprocessing**: Handling missing values, encoding categorical data, and feature scaling.
- **Exploratory Data Analysis (EDA)**: Visualizing the data to find patterns.
- **Model Training**: Using Logistic Regression for binary classification.
- **Model Evaluation**: Accuracy score, confusion matrix, and classification report.

## Results
The model predicts whether a passenger survived based on features like class, gender, age, and fare.

## Contributing
Feel free to fork the repository, make improvements, and submit a pull request.

---

*Developed with ❤️ for data science enthusiasts.*

