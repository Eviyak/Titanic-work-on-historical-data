# 🚢 Titanic Survival Prediction

This project analyzes historical data from the Titanic disaster and builds a machine learning model to predict whether a passenger would have survived. It includes detailed data exploration, preprocessing, and feature engineering using Python.

## 📄 Description

Using the Titanic dataset, we investigate how features like age, gender, ticket class, and other factors affected survival. The model is trained using logistic regression after visualizing relationships in the data and performing preprocessing steps such as handling missing values and extracting new features.

## 📁 Dataset

The project uses the classic [Titanic dataset](https://www.kaggle.com/c/titanic/data) containing data on passengers, such as:

- `Pclass` – Ticket class (1st, 2nd, 3rd)
- `Sex` – Gender
- `Age` – Age in years
- `SibSp` – # of siblings/spouses aboard
- `Parch` – # of parents/children aboard
- `Fare` – Ticket fare
- `Embarked` – Port of Embarkation
- `Survived` – 0 = No, 1 = Yes (target variable)

## 🔍 Features Engineered

- Age grouped into categories (Child, Teen, Adult, etc.)
- Extracted titles from names (Mr, Miss, Dr, etc.)
- Removed unnecessary columns (Cabin, Ticket)
- Handled missing data appropriately

## 📊 Data Visualization

Exploratory analysis was done using:
- Pie charts and countplots to show survival distribution
- Bar plots to show survival rate by gender and class
- Correlation and grouping to identify key predictors

## 🧠 Model

- **Algorithm:** Logistic Regression
- **Libraries used:** pandas, numpy, seaborn, matplotlib, scikit-learn
- **Metrics:** Accuracy score

## 🚀 How to Run

1. Open the notebook: `Work_with_historical_data_survived_on_Titanic.ipynb`
2. Run cells in order to:
   - Load and clean the dataset
   - Visualize insights
   - Train and evaluate the model

## ✅ Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook or Google Colab

## 📌 Notes

This project is for educational purposes and demonstrates a typical ML pipeline on a well-known dataset.

## 👩‍💻 Author

Created by Evelina Iakovleva as part of a university application portfolio.
