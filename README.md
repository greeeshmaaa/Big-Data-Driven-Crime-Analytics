# Big-Data-Driven-Crime-Analytics
Project Title

Big Data-Driven Crime Analytics: Scalable Data Processing & Predictive Intelligence for Urban Safety

Overview

This Jupyter Notebook contains the complete implementation of our crime analytics pipeline. The pipeline includes exploratory data analysis, classification modeling using XGBoost, clustering with KMeans, and forecasting with Facebook Prophet. Visual outputs, model evaluations, and actionable insights are presented within.

Requirements

Python 3.8+

PySpark

pandas, numpy, seaborn, matplotlib

xgboost

fbprophet (or Prophet)

folium

Jupyter Notebook or Google Colab

Setup Instructions

Clone the repository or open the notebook on a Jupyter Notebook environment.

Ensure all dependencies are installed:

pip install pyspark pandas numpy matplotlib seaborn xgboost prophet folium

Download the NYPD Complaint Historic Data from NYC Open Data.

Place the CSV in the working directory or modify the file path in the notebook.

Notebook Sections

Data Loading & Cleaning:

Load ~9M records with PySpark

Handle nulls, extract date-time features

Exploratory Data Analysis:

Borough-wise and time-based crime analysis

Visuals using Seaborn, Matplotlib, and Folium

Classification using XGBoost:

Classify crimes into Felony, Misdemeanor, Violation

Evaluate model with accuracy, precision, confusion matrix

Clustering with KMeans:

Detect crime hotspots via geospatial clustering

Visualize clusters on an interactive Folium map

Time Series Forecasting (Prophet):

Forecast daily crime count

Plot trends, seasonality, and future prediction intervals

Output Highlights

95.46% classification accuracy

10 optimized crime clusters

Clear daily/weekly crime trend forecasts

Authors

Greeshma Hedvikar, Jahnavi Kunapareddy, Chahat Dilip Kothari, Aryan Chauhan
