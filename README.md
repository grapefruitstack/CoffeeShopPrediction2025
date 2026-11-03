# CoffeeShopPrediction
Python based predictive modeling project analyzing coffee shop sales data using Pandas and Scikit-learn. Uses coffee shop sales data to identify purchasing patterns and develop machine learning models to predict which coffee drink a customer will purchase.

## Highlights
- Clean and prepare raw coffee shop sales data.
- Explore purchasing patterns across days, months, and times.
- Explore predictive models; decision tree vs logical regression.
- Identify which factors contribute to caffeine selection.
- Develop a machine learning model to predict those coffee purchases

## Description
This project was conducted to find out whether a decision tree classifier could predict which of the eight caffeinated drinks a customer would order at a specific cafe, based on hour of day, day of the week, and the month. If possible, it could support coffee shop managers by improving inventory planning, promotions, minimize waste, and increase general efficiency. The model was evaluated using accuracy and macro F1-score. 

The key findings were that time-based variables were not sufficient enough to predict drink choices. The decision tree model reached, at most, .234 baseline accuracy and a .186 F1-Score, which showed the model wasn’t predictive at all. Logistic regression had a validation accuracy of .251 and the test accuracy was .243, though the reasons for this higher accuracy are due to underfitting. 

Despite this, the model still can provide value. It reveals which variables are the most important for drink predicting - in this case, the weekday - and can teach shop owners to avoid relying on simple predictive models.

## Programs Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- SQLite

## Dataset
3,547 coffee shop sales records, March 2024 through March 2025.

Features:
- Coffee name
- Date
- Day of the week
- Hour of purchase

Prediction Target:
coffee_name

# Usage Instruction
Add all files in database to the google colab. 
