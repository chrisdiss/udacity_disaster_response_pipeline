# Project Disaster Response Pipeline

This project is part of the udacity Data Science Nanodegree Program. The objective of the project is to build a system that classifies disaster response messages automatically by using machine learning.

## Content
- Data
  - process_data.py: reads in the data, cleans and stores it in a SQL database. Basic usage is python process_data.py MESSAGES_DATA CATEGORIES_DATA NAME_FOR_DATABASE
  - disaster_categories.csv and disaster_messages.csv (dataset)
  - disaster_response_db.db: created database from transformed and cleaned data.
- Models
  - train_classifier.py: includes the code necessary to load data, transform it using natural language processing, run a machine learning model using GridSearchCV and train it.     Basic usage is python train_classifier.py DATABASE_DIRECTORY SAVENAME_FOR_MODEL
- App
  - run.py: Flask app and the user interface used to predict results and display them.
  - templates: folder containing the html templates

## Screenshots
