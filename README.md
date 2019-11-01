# Credit-Card-Fraud
The project is to compare the performance of an autoencoder with one-class SVM model in detecting fraud in credit card transactions. 

### Table of Contents

1. [Data](#data)
2. [Installation](#installation)
3. [Project Motivation](#motivation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Data <a name="data"></a>
The data has been anonymized due to privacy reason and it is publicly available here https://www.kaggle.com/mlg-ulb/creditcardfraud

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python and Keras.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

The project aims to compare the performance of an autoencoder with a more traditional algorithm namely one-class SVM. The metrics used to compare are Recall, Accuracy, Precision and F1-score. Given the highly unbalanced dataset, Recall was given more emphasize than the others.

Since an antoencoder reconstructs the inputs as its outputs, methods to make predictions will be explored. Their relationship with the performance metrics will be investigated.


## File Descriptions <a name="files"></a>

The notebook showing step by step from data exploration to discussion of the results obtained from the models.

### Folder: app

run.py - file to start the web application with files in the templates folder (go.html and master.html)

### Folder: data

disaster_messages.csv - real messages sent during disaster events provided by Figure Eight.

disaster_categories.csv - the categories of the messages.

process_data.py - to load raw messages, clean the messages and save the messages as inputs for Machine Learning model.

testing.db - a saved cleaned dataset.

ETL Pipeline Preparation.ipynb - notebook file in preparation for process_data.py (html is also provided).


## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@amaluddin11/best-indicators-for-day-traders-e029d526f336).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The Copyright and License information for the data can be referred at [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud) where the data was originally published. Otherwise, feel free to use the code here as you would like!
