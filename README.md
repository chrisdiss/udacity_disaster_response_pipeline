# Project Disaster Response Pipeline

This project is part of the udacity Data Science Nanodegree Program. The objective of the project is to build a system that classifies disaster response messages automatically by using machine learning.

## Code and Data
- Data
  - process_data.py: reads in the data, cleans and stores it in a SQL database. Basic usage is python process_data.py MESSAGES_DATA CATEGORIES_DATA NAME_FOR_DATABASE
  - disaster_categories.csv and disaster_messages.csv (dataset)
  - disaster_response_db.db: created database from transformed and cleaned data.
- Models
  - train_classifier.py: includes the code necessary to load data, transform it using natural language processing, run a machine learning model using GridSearchCV and train it.     Basic usage is python train_classifier.py DATABASE_DIRECTORY SAVENAME_FOR_MODEL
- App
  - run.py: Flask app and the user interface used to predict results and display them.
  - templates: folder containing the html templates

## Run

In a terminal navigate to the top-level project directory udacity_disaster_response_pipeline/ (that contains this README) and run commands in the following sequence:

1. cd data: python process_data.py disaster_messages.csv disaster_categories.csv disaster_response_db.db
2. cd .. cd models: python train_classifier.py ../data/DisasterResponse.db classifier.pkl
3. cd .. cd app: python run.py
Run the web application Go to http://0.0.0.0:3001/ (if facing problems try http://localhost:3001 in a browser)

In the web app you may input any text message (English) and it will categorize it among 35 classes.

## Screenshots

## Install
This project requires Python 3.x and the following Python libraries installed:

1. NumPy
2. Pandas
3. Matplotlib
4. Json
5. Plotly
6. Nltk
7. Flask
8. Sklearn
9. Sqlalchemy
10. Sys
11. Re
12. Pickle

## License
This app was completed as part of the Udacity Data Scientist Nanodegree. Code templates and data were provided by Udacity. The data was originally sourced by Udacity from Figure Eight.
