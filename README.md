# Cricket Score Predictor

Predict the final score of a cricket innings using machine learning.


## Project Objective

The goal of this project is to build a machine learning model that predicts the final runs scored in a cricket innings given the current match situation. This can help teams, commentators, and fans to understand potential outcomes during a match.


## Dataset

The dataset used in this project is included as `t20_wc.csv`. It contains match features such as batting_team, bowling_team, current_score, balls_left, wickets_left, crr, last_five, and runs_y.

Alternatively, you can download the dataset from [link if available].


## Key Features

- Preprocessing pipeline with one-hot encoding of categorical variables (teams)
- Feature scaling for numerical variables
- XGBoost regression model with hyperparameters tuned for performance
- Simple command-line interface to input match data and get final score prediction
- Model persistence using `pickle` for easy deployment


## Skills and Technologies Used

- Python programming
- Data preprocessing with `pandas` and `scikit-learn`
- Feature engineering using `ColumnTransformer` and `OneHotEncoder`
- Regression modeling with `XGBoost` and pipeline integration
- Model evaluation using R² score and mean absolute error (MAE)
- Saving and loading models using `pickle`
- Basic CLI for user interaction and prediction


## Example Prediction

Enter batting team: India
Enter bowling team: Australia
Enter current score: 130
Enter balls left: 36
Enter wickets left: 64
Enter current run rate: 7.2
Enter runs scored in last 5 overs: 45
Predicted final score: 152


## Conclusion

This project delivers a machine learning solution to predict cricket match final scores with reasonable accuracy using match state features. The use of pipelines ensures repeatability and ease of deployment. It can be extended further with more granular player-level data, weather conditions, and in-match factors for improved predictions.


