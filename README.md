Machine Learning Model 

This project allows you to upload a CSV file in Google Colab, choose feature columns, select a target column, and train two machine learning models. It then generates predictions, evaluates the models, and downloads a predictions file.

Features

Upload your own CSV dataset

Select feature columns and target column

Automatically cleans and prepares data

Trains two models: Linear Regression and Decision Tree

Generates predictions

Evaluates models using Mean Squared Error and R-squared

Saves predictions to a CSV file

Creates a visualization when using one feature

How It Works

Upload a CSV file when prompted

Enter the names of the feature columns

Enter the name of the target column

The script processes the data

Models are trained and evaluated

A predictions file is created and downloaded

A plot is shown if you use one feature

Output

The script produces:

A preview of your loaded dataset

Model scores for both Linear Regression and Decision Tree

A file named predictions.csv containing actual and predicted values

A scatterplot comparing predictions when one feature is used

Requirements

This code is designed to run in Google Colab and uses:

pandas

scikit-learn

matplotlib

google.colab for file upload and download
