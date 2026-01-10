Uber Fare Prediction Model

📌 Project Overview
The main objective of this project is to design an algorithm that predicts the fare to be charged for a passenger. Using machine learning techniques, specifically regression models, the system estimates travel costs based on various ride parameters.

❓ Problem Statement
Uber is one of the world's largest taxi companies, delivering services to millions of customers daily. This project focuses on predicting fares for future transactions by analyzing historical data. A fare calculator helps customers identify a valid fare for their trip, which is especially useful for tourists or people new to a city.

📊 Dataset Description
The dataset consists of approximately 200,000 samples with the following 8 variables:

key: A unique identifier for each trip.

fare_amount: The cost of each trip (Target Variable).

pickup_datetime: Date and time when the meter was engaged.

pickup_longitude: The longitude where the meter was engaged.

pickup_latitude: The latitude where the meter was engaged.

dropoff_longitude: The longitude where the meter was disengaged.

dropoff_latitude: The latitude where the meter was disengaged.

passenger_count: The number of passengers in the vehicle (driver entered value).

🛠️ Steps Involved
Data Exploration: Understanding the structure and types of data.

Data Cleaning: - Identifying and handling null values.

Removing outliers (e.g., negative fare amounts or impossible passenger counts).

Exploratory Data Analysis (EDA): Visualizing factors that affect the fare.

Feature Engineering: - Calculating travel distance (Haversine distance) from coordinates.

Extracting Hour, Day, Month, and Year from the timestamp.

Model Building: Implementing regression algorithms.

Evaluation: Comparing models based on RMSE (Root Mean Squared Error) and R2 Score.

🚀 Models Used
The project evaluates and compares different regression models:

Linear Regression

Random Forest Regression

💻 Requirements
To run this project, you need the following Python libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

📈 Conclusion
The Random Forest Regressor typically provides higher accuracy in predicting the fare compared to simple Linear Regression due to its ability to handle non-linear relationships in the geographical data.
