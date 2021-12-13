# Data Scientist Nanodegree
# Disaster Response Pipeline Project

### Introduction

• Identify the classes of the disaster message
• Applied ETL Pipeline Preparation & ML Pipeline Preparation then developed a flask application


In the Project Workspace, there are real messages that were sent during disaster events. created a machine learning pipeline to categorize these events so that to send the messages to an appropriate disaster relief agency.

This project  include a web app where an emergency worker can input a new message and get classification results on several categories. The web app will also display visualizations of the data.

### Steps:

- ETL Pipeline In a Python script, process_data.py, write a data cleaning pipeline that: Loads the messages and categories datasets Merges the two datasets Cleans the data Stores it in a SQLite database

- ML Pipeline In a Python script, train_classifier.py, write a machine learning pipeline that: Loads data from the SQLite database Splits the dataset into training and test sets Builds a text processing and machine learning pipeline Trains and tunes a model using GridSearchCV Outputs results on the test set Exports the final model as a pickle file

- Flask Web App will be taking the user message and classify them into 36 categories. There are some beautiful visualization of the data as well


### Install

- [NumPy]
- [Pandas]
- [matplotlib]
- [scikit-learn]
- [NLTK]

### Run
Run the following commands in the project's root directory to set up your database and model.

To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
Run the following command in the app's directory to run your web app. python run.py

Go to http://localhost:8000/

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go tohttp://localhost:8000/

### data 
https://drive.google.com/file/d/1JiU4QRz8TLKMBUypLSYjTGJ-M5B5L3kX/view?usp=sharing
