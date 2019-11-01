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

In this project, I was originally interestested in identifying the best technical indicators to predict stock price movement, either up or down using pre-calculated technical indicator based on historical stock data. In the attempts to achieve this, I have realized that the accuracy obtained is not as high as I had hoped for. Therefore, this project then aims to

1. Compare the accuracy of prediction using SVW, SVM with PCA, and Neural Networks.
2. What are the most weighted indicators in the top PCA components?
3. Based on this data, can we visualize the data to see if we can really separate the two classes, price up or down?


## File Descriptions <a name="files"></a>

The notebook showing step by step from data cleaning to the three models is available here.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@amaluddin11/best-indicators-for-day-traders-e029d526f336).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The Copyright and License information for the data can be referred at [Elsevier Data in Brief](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5219605/) where the data was originally published. Otherwise, feel free to use the code here as you would like!

