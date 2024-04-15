# NHL Game Outcome Prediction

### Overview

This project aims to develop a machine learning model to predict the outcomes of NHL (National Hockeyt League) games based on historical data. By analyzing various feautures such as team statistics and game conditions, the model seeks to provide insights into the factors influencing the game results and improve the accuracy of outcome predictions.

### Dependencies

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

### Dataset

The dataset used in this project is from moneypuck.com and it consists of historical NHL game data, including basic and advanced statistics from 2008-2023. Full dataset can be download from [here](https://moneypuck.com/moneypuck/playerData/careers/gameByGame/all_teams.csv)

#### Features:

- Team statistics (goals scored, shots on goal, power play percentage, etc.)
- Game conditions (Home or Away, Playoff Game)

#### Preprocessing:

- Value Imputation
- Feauture scaling
- Encoding categorical variables

### Machine Learning Model

We employed a supervised learning approach to predict game outcomes. The following algorithms were experimented with:

- Logistic Regression
- Neural Networks
- Random Forest Classifier

#### Model Evaluation

Model performance was evaluated using the following metric

- Accuracy

### Results

The Neural Networks model outperformed the other algorithms, achieving an accuracy of 95% on the test set.

### Future Work

- Incorporate real-time data for more accurate predictions
- Explore advanced machine learning techniques such as gradient boosting machines
- Integrate function to incorporate player injuries impact on team stats

### Author

- Jason Lew (@jasonwlew) - jasonw.lew@outlook.com