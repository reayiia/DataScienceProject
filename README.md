# DataScienceProject
Data Science Project on NFL Stats

# NFL Player Salary and Performance Analysis (2017)

This repository contains the full deliverables for a data science project analyzing the relationship between NFL player performance metrics and their salary cap impact. The project was completed as part of the COMP3125 Data Science Fundamentals course.

## 📌 Project Overview

The goal of this project is to explore whether NFL player salaries can be predicted based on their performance statistics using a regression model. A simulated dataset was used due to limited access to real-world advanced NFL metrics.

### 🔍 Key Objectives:
- Combine salary and performance data into a single dataset
- Simulate player statistics based on position logic
- Apply a multiple linear regression model
- Evaluate model performance using R², MAE, and RMSE
- Analyze which metrics are most influential in predicting salary
---

## 📊 Data Sources

- **Salaries:** [Kaggle NFL 2017 Salaries Dataset](https://www.kaggle.com/datasets/adhurimquku/nfl-player-salaries-and-statistics)
- **Performance Reference:** [Pro Football Reference 2017](https://www.pro-football-reference.com/years/2017/)
- **Cap Data:** [Spotrac Salary Rankings](https://www.spotrac.com/nfl/rankings/_/year/2017)

> 🧪 Note: Player performance statistics were **simulated** to reflect typical 2017 values by position.

---

## 🧠 Model Summary

- **Model Type:** Multiple Linear Regression
- **Framework:** scikit-learn (Python)
- **Performance:**
  - R²: -0.045 (poor fit)
  - MAE: ~$1.25M
  - RMSE: ~$1.9M
