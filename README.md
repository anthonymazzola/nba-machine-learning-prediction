
# NBA Win Prediction

This project applies machine learning models to predict the outcomes of NBA games using team statistics and ELO scores. Our goal is to achieve prediction accuracies between 60% and 70%, which can provide valuable insights into sports analytics and potentially be used in sports betting.

## Project Overview

We utilize various machine learning algorithms, including:

- **Logistic Regression**
- **Naive Bayes**
- **Support Vector Machines (SVM)**
- **Random Forest**
- **Multilayer Perceptron Neural Network (MLP)**

The dataset includes team statistics (such as field goal percentage, offensive/defensive rebounds, assists, etc.) and advanced metrics like ELO score, offensive rating, and defensive rating.

### Data Sources:
- **Team statistics**: Pulled from [NBA.com](https://www.nba.com/stats) using the [nba-api](https://github.com/swar/nba_api).
- **ELO Scores**: Sourced from [FiveThirtyEight](https://github.com/fivethirtyeight/data/tree/master/nba-forecasts).

### Project Highlights:
- Used data from the 2012-13 to 2020-21 NBA seasons for training.
- Tested on data from the 2021-22 NBA regular season.
- Best performing model: **Random Forest** with 61.04% accuracy.
- Evaluation methods: Accuracy, Precision, Recall, Confusion Matrix, ROC Curve.

## Future Improvements
- Implement weighted averages for team statistics (emphasizing recent games).
- Perform feature pruning to improve model performance.
- Explore additional advanced analytics for better prediction accuracy.
