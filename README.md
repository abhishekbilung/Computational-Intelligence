
# Predictive Maintenance for IoT Devices using Random Forest Classifier with Genetic Algorithm for Feature Selection

This project focuses on predictive maintenance for IoT devices using machine learning techniques, specifically the Random Forest classifier. It also incorporates a Genetic Algorithm (GA) to optimize the feature selection process, ensuring that the most relevant and impactful features are used for model training. The aim is to predict the failure of IoT devices based on sensor data and perform maintenance proactively.
Key Features:

IoT Device Data Simulation: The project uses data collected from IoT sensors attached to devices to track health metrics such as temperature, vibration, and operational hours.
Random Forest Classifier: The Random Forest algorithm is applied to classify devices as either 'Healthy' or 'At Risk' based on sensor readings.
Feature Selection with Genetic Algorithm: A Genetic Algorithm (GA) is used to identify the best features for the Random Forest model, optimizing performance by selecting only the most relevant ones from the dataset.
Selection: GA selects the most important features based on fitness criteria (e.g., predictive power of features).
Crossover & Mutation: These genetic operations help explore different feature subsets, improving the model’s generalization.
Data Preprocessing: The data is cleaned and preprocessed with techniques like handling missing values, normalization, and encoding categorical variables.
Model Evaluation: The model is evaluated using performance metrics such as accuracy, precision, recall, and F1-score to ensure its reliability and effectiveness.
 Real-time Prediction (Optional): The system can be adapted for real-time monitoring and prediction of IoT device health, providing alerts when maintenance is required.

Objective:

The main goal of this project is to predict the failure of IoT devices by utilizing historical sensor data. The project aims to:

Apply a Random Forest classifier to predict the health status of IoT devices.
Use a Genetic Algorithm (GA) to optimize feature selection, improving the model's performance by identifying the most relevant features.
Offer a proactive approach to maintenance, helping industries avoid unexpected device failures and minimize downtime.

By combining machine learning with genetic optimization, this project provides a powerful tool for predictive maintenance in IoT networks, reducing maintenance costs and improving the reliability of the devices.
How to Run the Code:

clone the repository to your local machine:

    git clone 

Navigate to the project directory:

    cd Computational-Intelligence/Genetic-ALgorithm

Install the required dependencies:

    pip install -r requirements.txt

Run the Python script to train the model with feature selection:

    python main.py

The model will output predictions and performance metrics like accuracy, precision, recall, and F1-score.
