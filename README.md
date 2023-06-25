# **USA House Price Prediction**


This project focuses on predicting house prices in the USA using machine learning regression algorithms. The repository contains the implementation of 7 regression algorithms, including Linear Regression, Random Forest Regressor, Gradient Boosting Regressor, SVR, DecisionTreeRegressor, ElasticNet, and XGBRegressor. The goal is to identify the best-performing regression model for house price prediction.

## ***Website Interface***

![Screenshot (94)](https://github.com/AmitBhowmick01/Final-Assignment-House-Price-Prediction/assets/126709893/a1b55367-468f-42c3-8f08-61ab10dc17f2)


## Algorithms Used

1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor
4. SVR (Support Vector Regressor)
5. DecisionTreeRegressor
6. Ridge
7. XGBRegressor

## Data

The project utilizes a dataset containing features related to house prices in the USA. The dataset is preprocessed and used for training and testing the regression models.

## Model Evaluation

The performance of each regression algorithm is evaluated using the R2 score. After evaluating all the models, the top 3 models with the highest R2 scores are selected.

## Pickle File

A pickle file is created for the best-performing regression model, which is the 'Random Forest Regressor' in this case. The pickle file contains the trained model, ready to be deployed for predictions.

## Deployment

To deploy the model, a Flask application is developed. The Flask application serves as an API endpoint that accepts house features as input and returns the predicted house price. An HTML file is created to provide a user-friendly interface for interacting with the deployed model.

## Testing

To test the deployed model, it is recommended to set up a virtual environment to maintain a clean and isolated environment. You can use tools like virtualenv or conda to create a virtual environment and install the required dependencies. Once the environment is set up, you can run the Flask application and access the prediction functionality through the provided HTML interface.

## Repository Structure

The repository is organized as follows:

- `data/`: Contains the dataset used for training and testing.
- `models/`: Contains the pickled model file.
- `app.py`: Flask application file for model deployment.
- `templates/`: Contains the HTML file for the user interface.
- `requirements.txt`: Lists the dependencies required to run the Flask application.
