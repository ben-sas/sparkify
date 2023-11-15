# Udacity Data Science Capstone Project: Sparkify Churn Prediction

This repository contains the code of my Udacity Nanodegree capstone project "Sparkify". The goal was to predict churn based on user log data of a fictional music streaming service. Instead of using libraries like Pandas and scikit-learn, the challenge was to code the whole analysis, ETL pipeline and model pipeline with PySpark.


# Data

While the whole dataset for Sparkify is available on AWS, this Jupyter notebook focuses on a small subset. Since even the subset is larger than 100MB, it is included as a zip-file in the repository. To run the notebook, simply extract the data in the main folder.

- mini_sparkify_event_data.zip


# Libraries

The following libraries are required to run the code and need to be installed in the virtual environment:

Library	  				    | Comments
-------------				    | -------------
findspark				    | Facilitates the use of PySpark without additional setup.
pyspark 				    | Make sure that you have an updated version of JDK (Java Development Kit) installed.
datetime                                    | -
numpy                                       | -
pandas                                      | -
matplotlib                                  | -




<br>


# Description of files in repository

File Name	  			    | File Description
-------------				    | -------------
README.md				    | Readme file.
mini_sparkify_event_data.zip 		    | Zipped data extract. Unzip locally on your machine.
Sparkify.ipynb                              | Jupyter Notebook with the analysis, ETL pipeline and model.


<br>


# How to run the analysis on your machine

1. Download and install an updated version of JDK

2. Unzip the data file locally
        
3. Have fun running and modifying the Jupyter Notebook :)