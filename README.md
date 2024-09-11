
# NFL Rushing Statistics Prediction

This project analyzes NFL rushing statistics from 2001 to 2023 and predicts rushing touchdowns based on various player statistics such as rushing attempts, rushing yards, and age. The project utilizes machine learning models to make predictions and visualize key insights.

## Project Overview

The dataset used contains the rushing statistics for NFL players over 22 seasons. The goal of this project is to build machine learning models to:
1. Classify players based on fumble frequency.
2. Predict a player’s rushing touchdowns using their performance statistics.

### Dataset
- **Source**: [NFL Rushing Statistics 2001-2023](https://www.kaggle.com/datasets/rishabjadhav/nfl-rushing-statistics-2001-2023)
- Fields include: Player name, age, games played, rushing attempts, rushing yards, rushing touchdowns, first downs, and fumbles, among others.

## Features

- **Data Preprocessing**: Cleaned and prepared the dataset, handled missing values, and filtered out players with fewer than 120 rushing attempts.
- **Exploratory Data Analysis (EDA)**: Analyzed basic statistics and visualized trends using scatter plots, histograms, and feature importances.
- **Machine Learning Models**:
  - Logistic Regression for classification (fumble frequency).
  - Random Forest for classification and regression.
  - Polynomial Regression to predict rushing touchdowns.
  - Decision Trees to analyze feature importance.

## Installation and Setup

### Requirements
- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `statsmodels`

You can install the required libraries by running:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

## Running the Project

Clone this repository to your local machine:

```bash
git clone https://github.com/Chasem11/NFL-Rushing-Statistics.git
```
### Results

- **Classification**: The Logistic Regression model was used to classify players based on fumble frequency (over/under 4 fumbles), achieving an accuracy of around 72%.
- **Regression**: Polynomial Regression and Random Forest were used to predict rushing touchdowns based on player statistics, with varying degrees of accuracy.

### Visualizations

Several visualizations were created to explore trends in the data:

- Scatter plots of rushing attempts vs. rushing yards.
- Histograms of fumble frequencies.
- Feature importance plots from Random Forest.

