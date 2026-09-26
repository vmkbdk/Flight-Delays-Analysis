# Flight Delays Analysis Project ✈️

## 📝 Project Overview
This project provides a comprehensive analysis of flight delays using a sample dataset of 3 million flights. The primary goal is to identify patterns in flight delays, understand their root causes, and explore the relationship between different operational factors such as airline, distance, and time of year.

## 🎯 Business & Analytical Questions
The analysis is structured around five key questions:
1.  Airline Performance: Which airlines operate the highest volume of flights, and what are the flight cancellation and delay statistics for each carrier?
2.  Delay Behavior: What is the statistical distribution of departure and arrival delays, and what is the key difference between the Mean and Median delay times?
3.  Temporal Patterns: Do delay rates and average delay durations vary significantly by days of the week or months of the year?
4.  Distance vs. Delay Relationship: Does flight distance have a direct positive impact on delay duration, and what is the correlation coefficient value?
5.  Multiple Delay Causes: What are the statistical relationships and correlations among various delay causes (Weather, Carrier, NAS, Late Aircraft), and which cause is the primary driver?

## 📊 Dataset
The dataset used in this analysis is flights_sample_3m.csv. Due to its large size, it cannot be uploaded directly to GitHub. It can be downloaded from the original source on Kaggle:
https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023

## 🛠️ Technologies Used
- Python 3
- Pandas: For data manipulation and cleaning.
- NumPy: For numerical operations.
- Matplotlib & Seaborn: For creating insightful data visualizations.
- Jupyter Notebook: As the development environment.

## 📈 Analysis & Key Findings
1.  Airline Performance: Major airlines like WN, DL, and AA dominate the flight volume.
2.  Delay Behavior: Delay times are heavily right-skewed. The median delay is much lower than the mean, indicating that while most flights are on time or slightly delayed, a small number of extreme outliers pull the average up.
3.  Temporal Patterns: Delays tend to be slightly higher on weekends (Friday and Sunday). Seasonally, summer months (June, July) and December show higher average delays.
4.  Distance vs. Delay: There is a very weak positive correlation (~0.02) between flight distance and departure delay. Flight distance is not a significant factor in causing delays.
5.  Delay Causes: The most significant and recurring cause of delays is LATE_AIRCRAFT, followed by CARRIER delays. There is a very strong positive correlation (0.96) between departure and arrival delays.

## 🚀 How to Use This Repository
1.  Ensure you have the required libraries installed (pip install pandas numpy matplotlib seaborn).
2.  Download the flights_sample_3m.csv dataset from the link provided above and place it in the project directory.
3.  Run the Jupyter Notebook Flight_Delays_Analysis.ipynb to see the full analysis.
