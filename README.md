# Titanic Decision Tree Classifier

This project implements a Decision Tree Classifier to predict the survival of passengers on the Titanic using the Titanic dataset. The model is trained on various demographic and behavioral features to determine the likelihood of survival.

## Dataset

The dataset used for this project is the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data). The data can be found in the `data/` directory.

## Features

The dataset includes the following features:

- `Pclass`: Ticket class (1st, 2nd, 3rd)
- `Sex`: Gender of the passenger
- `Age`: Age of the passenger
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Fare`: Ticket fare
- `Embarked`: Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## Installation

To run this project, ensure you have the following Python packages installed:

```bash
pip install -r requirements.txt
