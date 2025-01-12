<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/abhaygill">
    <img src="https://img.freepik.com/premium-vector/fire-mountain-logo-design-unique-concept-simple-style-premium-vector_632138-4140.jpg?ga=GA1.1.1288798671.1736712425&semt=ais_hybrid" alt="Logo" width="100" height="100"/> 
  </a>

<h1 align="center">Wildlife Fire Prediction System</h1>

  <p align="center">
    AMachine Learning Project
    <br />
    <a href="https://github.com/abhaygill/Wildlife-Fire-Prediction-System"><strong>Explore the Repo »</strong></a>
    <br />
    <br />
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## Project Overview
This project leverages Data Science and Machine Learning to predict forest fires based on weather conditions. The solution is supported by a comprehensive pipeline involving:
* Storage of dataset in MongoDB Atlas for efficient data handling.
* A user-friendly Flask Web Application, hosted on Heroku for accessibility.
* Extensive use of libraries such as Sklearn for modeling and Pandas, Numpy, Matplotlib for data manipulation, processing, and visualization.



<!-- GETTING STARTED -->
## Introduction
The project utilizes the Algerian Forest Fires Dataset from UCI Machine Learning Repository, comprising forest fire observations from two distinct regions of Algeria: Bejaia and Sidi Bel-Abbes.
*  The dataset spans June 2012 to September 2012, containing critical weather metrics.
*  The objective is to predict forest fires using classification and regression models, focusing on weather-driven features.

<!-- USAGE EXAMPLES -->
## Key Features

### 1. End-to-End Data Pipeline:
* Extracted and processed dataset from UCI.
* Data uploaded to MongoDB Atlas, integrated via pymongo.

### 2. Data Exploration and Insights:
* Conducted Exploratory Data Analysis (EDA) to uncover patterns influencing fire occurrences.
* Visualized key trends using Matplotlib and Seaborn.

### 3. Machine Learning Models:
* Classification Task: Binary prediction (fire, not fire) using algorithms like Logistic Regression, Random Forest, and XGBoost.
* Regression Task: Predicting the Fire Weather Index (FWI) with models such as Ridge Regression, KNN Regressor, and Support Vector Regressor.

### 4. Model Selection and Optimization:
* Fine-tuned models using Randomized GridSearch CV for hyperparameter optimization.
* Employed Stratified K-Fold Cross-Validation for robust evaluation in classification and R² score for regression tasks.

### 5. Web Application Deployment:
* Developed a Flask-based interface for user interaction.
* Deployed on Heroku, allowing real-time predictions via simple input forms.

### 6. Loading CSV and Inserting to DB
* The Downloaded CSV file is loaded as pandas Dataframe using Pandas Library.
* Pandas Dataframe is converted to Dict .
* Mongodb Altas is used as DB here, with `pymongo library` mongodb is connected to python.
* Database and collections created via python and the list of dictionaries is uploaded using `collection.insert_many` method.

<p align="right">(<a href="#top">back to top</a>)</p> 

## Implementation Steps
### 1. Environment Setup
* Installed Python, PyCharm, MongoDB, and Git.
* Configured Flask and connected it with MongoDB Atlas.
### 2. Data Processing
* Loaded and cleaned data using Pandas, converting it into a dictionary format for database insertion.
* Uploaded data into MongoDB collections using insert_many for efficient handling.
### 3. EDA and Visualization
* Identified key weather parameters affecting fire occurrences.
* Created detailed visualizations using Matplotlib and Seaborn to extract actionable insights.
### 4. Model Training
* Implemented both classification and regression algorithms, using features like FWI and weather metrics for predictions.
* Evaluated models based on accuracy and R² scores, optimizing them with hyperparameter tuning.
### 5. Flask Application
* Designed a Flask web interface with routes for default pages and prediction endpoints (/predict, /predictR).
* API testing facilitated through Postman.
### 6. Deployment on Heroku
* Uploaded the application repository to GitHub.
* Deployed the app using Heroku CLI, ensuring seamless integration and real-time functionality.

<p align="right">(<a href="#top">back to top</a>)</p>

