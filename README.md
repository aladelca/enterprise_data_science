# Predicting soccer player market value using machine learning
Author: Adrian Alarcon


## About 🚀


The current project, as part of the course of Enterprise Data Science, is an end-to-end machine learning project where the ultimate goal is to predict the value of a soccer player (in euros) based on their characteristics such as ratings in every skill, club, years of contract, salary, release clause, among others. This project included three parts:

1. Data extraction: the dataset was created scrapping the webpage [sofifa.com](https://sofifa.com/players) where the features has been extracted. You can find more detailed about the data extraction process in the `data_extract.py` file.
2. Data cleaning: several steps in terms of data cleaning has been made such as spliting values and getting correct format of variables.
3. Training & evaluating a machine learning: in this step, feature engineering process and validation schemas has been proposed. To test the model, I have decided to split the dataset in three parts: train, test, validation. Train and test have been used to training the model and calibrate hyperparameter, while validation dataset was used to validate the final model and the final metrics