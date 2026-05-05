PhonePe Transaction Insights using Data Analytics and Machine Learning
Overview

This project analyzes PhonePe transaction data to understand patterns in digital payments across India. It applies data analytics, visualization techniques, and machine learning models to generate meaningful insights and predictions.

Objectives
Analyze transaction trends across different states and time periods
Identify commonly used payment categories
Perform exploratory data analysis using multiple visualizations
Build machine learning models to predict transaction amounts
Develop an interactive dashboard using Streamlit
Dataset

The dataset is sourced from the PhonePe Pulse GitHub repository.

It includes:

State-wise transaction data
Year and quarter details
Transaction types
Transaction count
Transaction amount
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
MySQL
Streamlit
Exploratory Data Analysis (EDA)

The dataset was analyzed using multiple visualization techniques such as:

Bar charts
Pie charts
Line graphs
Scatter plots
Heatmaps
Key Insights
Digital transactions show consistent growth over time
Peer-to-peer payments are the most frequently used category
Some states contribute significantly higher transaction volumes
A strong relationship exists between transaction count and transaction amount
Digital payment adoption is increasing steadily across regions
Machine Learning Models

The following models were implemented:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
K-Nearest Neighbors (KNN)
Support Vector Regression (SVR)
Model Performance
Random Forest provided the best results
Linear Regression served as a baseline model
Tree-based models captured complex patterns effectively
Streamlit Dashboard

An interactive dashboard was created using Streamlit to visualize:

State-wise transaction trends
Payment type distribution
Year-wise growth
Correlation between variables
Run the Dashboard
streamlit run app.py
Project Structure
PhonePe-Transaction-Insights
│
├── PhonePe_EDA.ipynb
├── PhonePe_ML_Model.ipynb
├── app.py
├── phonepe_data.csv
├── README.md
├── LICENSE
Conclusion

This project demonstrates how data analytics and machine learning can be used to analyze transaction behavior and predict trends. The results highlight the increasing use of digital payments and the importance of data-driven insights.

Future Scope
Integration with real-time data sources
Implementation of advanced machine learning models
Development of fraud detection mechanisms
Deployment of the dashboard on cloud platforms
Author

Arjya Keshari Biswal
B.Tech Computer Engineering

Acknowledgement

The dataset used in this project is obtained from the PhonePe Pulse GitHub repository.
