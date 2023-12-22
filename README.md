# SpaceX Falcon 9 Landing Prediction Capstone

## Overview
In this capstone project, we aim to predict the successful landing of the Falcon 9 first stage after a rocket launch by SpaceX. The ability to predict the landing success is crucial for estimating the cost of a launch. SpaceX's cost advantage lies in the reusability of the first stage, allowing for significant cost savings compared to other providers. This predictive model could be invaluable for potential competitors looking to bid against SpaceX for rocket launches.

## Notebooks Overview

### 1. Data Collection from API
- In the first notebook, data is collected from an API to ensure it is in the correct format. This step is fundamental for the subsequent analysis and prediction tasks.

### 2. Web Scraping Falcon 9 Historical Launch Records
- The second notebook involves web scraping to collect historical launch records of Falcon 9 from a Wikipedia page titled "List of Falcon 9 and Falcon Heavy launches."

### 3. Exploratory Data Analysis (EDA)
- The third notebook performs Exploratory Data Analysis (EDA) to discover patterns in the data and determine the label for training supervised models.

### 4. Understanding SpaceX DataSet and Database Interaction
- The fourth notebook aims to understand the SpaceX dataset, load it into a corresponding table in a Db2 database, and execute SQL queries to answer assignment questions.

### 5. More EDA and Feature Engineering
- In the fifth notebook, additional Exploratory Data Analysis and Feature Engineering are conducted to prepare the data for model training.

### 6. Interactive Visual Analytics with Folium
- The sixth notebook leverages Folium for more interactive visual analytics, providing insights into spatial patterns and correlations in the data.

### 7. SpaceX Dash App
- The seventh notebook focuses on creating a SpaceX Dash app for a more user-friendly and interactive experience.

### 8. Model Training and Evaluation
- The eighth notebook involves:
  - Creating a column for the class (landing success).
  - Standardizing the data.
  - Splitting the data into training and test sets.
  - Finding the best hyperparameters for SVM, Classification Trees, and Logistic Regression.
  - Determining the method that performs best using test data.
