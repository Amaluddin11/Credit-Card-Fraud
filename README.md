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

The notebook showing step by step from data cleaning to the three models is available here.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@amaluddin11/best-indicators-for-day-traders-e029d526f336).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The Copyright and License information for the data can be referred at [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud) where the data was originally published. Otherwise, feel free to use the code here as you would like!
