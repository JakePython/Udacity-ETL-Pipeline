# Udacity-ETL-Pipeline

Visualisations

![image](https://user-images.githubusercontent.com/33510119/116252267-b2542700-a76f-11eb-991c-1a29a1a54924.png)

![image](https://user-images.githubusercontent.com/33510119/116252431-da438a80-a76f-11eb-835d-1f2e02568892.png)

![image](https://user-images.githubusercontent.com/33510119/116252525-f2b3a500-a76f-11eb-99b6-0a3d72ee278d.png)

Disaster Response Pipeline Project

Figure Eight has provided data related to messages, categorized into different classifications, that have been received during emergencies/disasters. This project attempts to recognize these categories in order to cater for quicker responses to the emergency messages. Using machine learning techniques, we should be able to predict the category.

Installation
This project requires Python 3.x and the following Python libraries installed:

-NumPy
-Pandas
-Matplotlib
-Json
-Plotly
-Nltk
-Flask
-Sklearn
-Sqlalchemy
-Pickle

The process was carried out as follows:
1.	Data Processing Assessing and cleaning the data, so that it can be utilized by machine learning algorithms. See details in the ../data/process_data.py .
2.	Model training Data was passed through a pipeline and a prediction model is made. See details in the ../models/train_classifier.py 
3.	Prediction and Visualization Making a web app for prediction and visualization, where user may try some emergency messages and see visualization of distribution of genres and categories.

Instructions:
Run the following commands in the project's root directory to set up your database and model.

To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
Run the following command in the app's directory to run the web app. python run.py

Go to https://view6914b2f4-3001.udacity-student-workspaces.com/

File structure of project:
../app - folder for web app
../app/run.py - flask web app

../data - folder for files for the datasets
../data/disaster_categories.csv - raw file containing the categories
../data/disaster_messages.csv - raw file containing the messages
../data/process_data.py
../data/DisasterResponse.db - database for the clean data

../models - folder for the classifier model and pickle file
../models/train_classifier.py - model training script

Acknowledgements:
Figure8 for the data
Udacity for the ETL Pipeline course 

