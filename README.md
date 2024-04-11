# Crop_Recommendation_System

The Crop Recommendation System is a machine learning-based application that provides personalized recommendations for crop cultivation based on various environmental and soil factors. This application aims to assist farmers, agricultural advisors, and other stakeholders in making informed decisions about which crops to cultivate in specific conditions.

# Table of Contents
Overview 

Features

Installation

Usage

Technologies Used

Data

Model

Contributing

# Overview
The Crop Recommendation System utilizes machine learning algorithms to recommend the most suitable crops to cultivate based on input data such as soil nutrients (Nitrogen, Phosphorus, Potassium), climatic conditions (Temperature, Humidity, Rainfall), and soil pH. The system provides an intuitive web-based interface that allows users to input these factors and receive real-time crop recommendations.

# Features
User-Friendly Interface: The web application features a clean and simple form for users to input environmental and soil data.
Real-Time Recommendations: Upon submission of data, the application uses a trained machine learning model to provide crop recommendations immediately.
Data Preprocessing: The system employs MinMax and Standard scaling to preprocess input data, ensuring compatibility with the trained model.
Persisted Model and Scalers: The trained machine learning model and data scalers are persisted using pickle for efficient and consistent predictions.

# Installation
1. Clone the repository:
   
git clone https://github.com/aru-b/Crop_Recommendation_System.git

2. Navigate to the project directory:
   
cd crop-recommendation-system

3. Install the required Python packages:
   
pip install -r requirements.txt

4. Start the application:
   
python app.py

# Usage
Launch the application as described in the installation section.
Navigate to localhost in your web browser.
Fill in the form with the required environmental and soil data.
Click the "Get Recommendation" button.
The recommended crop for cultivation based on the input data will be displayed.

# Technologies Used
Flask: A lightweight web framework used for building the web application.

Pandas: A data manipulation and analysis library used for data handling.

NumPy: A library used for numerical operations and data manipulation.

Scikit-learn: A machine learning library used for model development and evaluation.

Seaborn and Matplotlib: Libraries used for data visualization.

Bootstrap: A front-end framework used for styling the web application.

# Data
The application uses a dataset containing information on soil nutrients, climatic conditions, and soil pH, along with corresponding crop labels. This data is used to train the machine learning model to provide accurate crop recommendations.

# Model
The machine learning model used in the application is a Random Forest Classifier. It is trained on the dataset to predict the most suitable crop for cultivation based on input data. The model and data scalers (MinMax and Standard) are persisted using pickle for quick loading and predictions.

# Contributing
Contributions are welcome! If you would like to contribute to the project, please follow these steps:

Fork the repository.
Create a new branch for your changes.
Commit your changes.
Push your changes to your forked repository.
Submit a pull request.
