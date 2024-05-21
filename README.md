NBA Player Age vs. Points Per Game Analysis
This project aims to explore the relationship between NBA players' ages and their points per game (PPG) statistics using machine learning techniques. The analysis is performed on data from the 2023-2024 NBA season.
Overview
The primary goal of this project is to build a predictive model that can estimate a player's points per game based on their age and potentially other relevant features. Linear regression is employed as the main modeling technique, leveraging popular Python libraries such as scikit-learn, pandas, seaborn, and matplotlib.


The dataset used in this analysis is the "2023-2024 NBA Player Stats - Regular" dataset from Kaggle, which can be found below. It contains various player statistics from the 2023-2024 NBA season, including age, points per game, minutes played, position, team, and previous season statistics (if available). The data has been preprocessed to handle missing values, remove outliers, and encode categorical variables into a numerical format suitable for linear regression.
Dataset: https://www.kaggle.com/datasets/vivovinco/2023-2024-nba-player-stats?resource=download&select=2023-2024+NBA+Player+Stats+-+Regular.csv

Methodology
1. Data Preprocessing: The raw data is cleaned and prepared for analysis, including handling missing values, removing outliers, and encoding categorical variables.

2. Exploratory Data Analysis (EDA): Visualizations are created using seaborn and matplotlib to explore the relationships between variables and identify potential patterns or outliers in the data.

3. Model Training: A linear regression model is trained using scikit-learn's LinearRegression class, with the selected features as input and points per game as the target variable.

4. Model Evaluation: The trained model's performance is evaluated using appropriate metrics such as mean squared error (MSE) and R-squared (R²). Visualizations are created to assess the model's fit and identify potential areas for improvement.

5. Interpretation: The model coefficients and their statistical significance are interpreted to understand the impact of each feature on the target variable (points per game).
