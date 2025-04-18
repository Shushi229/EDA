## Titanic Dataset Exploratory Data Analysis
This repository contains an exploratory data analysis (EDA) of the famous Titanic dataset, which includes information about the passengers aboard the RMS Titanic and whether they survived the shipwreck.
Project Overview

## The analysis explores various factors that might have influenced survival rates among passengers, including:

Passenger class
Gender
Age
Fare paid
Port of embarkation
Family size

## Files in this Repository

**EDA_TITANIC.ipynb**: Jupyter notebook containing the full analysis with code and visualizations
**EDA_TITANIC.pdf**: PDF export of the notebook with all visualizations and findings
**Titanic.csv**: The dataset used for the analysis

## Key Findings

**Females had significantly higher survival rates than males**
**Passengers in higher classes (1st class) had better chances of survival**
**Young children had slightly higher survival rates**
**There was a positive correlation between fare paid and survival chances**
**Missing values were prevalent in the Age and Cabin columns**

## Tools & Libraries Used

Python 3.x
Pandas for data manipulation
Matplotlib and Seaborn for data visualization

## How to Run

Clone this repository
Install the required dependencies:
pip install pandas matplotlib seaborn jupyter

Open the Jupyter notebook:
jupyter notebook EDA_TITANIC.ipynb


## Data Description
**The dataset contains the following features:**

PassengerId: Unique identifier for each passenger

Survived: Survival status (0 = No, 1 = Yes)

Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name: Passenger name

Sex: Passenger gender

Age: Passenger age

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Fare paid for ticket
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
