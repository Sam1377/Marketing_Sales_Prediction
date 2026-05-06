Marketing Sales Prediction using Machine

🚀 Overview

This project focuses on predicting product sales based on marketing spend across different advertising channels. Using data-driven techniques, we analyze how investments in marketing (TV, Radio, Newspaper, etc.) impact sales performance and build a predictive model to optimize business decisions.

The goal is to help businesses maximize ROI on marketing campaigns by identifying the most effective channels.


🎯 Objectives


Understand the relationship between marketing spend and sales
Perform data cleaning and exploratory data analysis (EDA)
Build a machine learning model to predict sales
Evaluate model performance using key metrics
Provide actionable business insights


📁 Dataset DescriptionThe 


dataset contains marketing spend across different channels and corresponding sales.
Features:

TV – Advertising spend on TV
Radio – Advertising spend on radio
Newspaper – Advertising spend on newspaper
Sales – Target variable (product sales)


🔍 Exploratory Data Analysis (EDA)


Key steps performed:
Checked for missing values and duplicates
Analyzed feature distributions
Correlation analysis between marketing channels and sales
Visualizations to identify trends and patterns


📌 Key Insight:

TV advertising showed the strongest correlation with sales, while newspaper had minimal impact.


⚙️ Model Building

Algorithm Used: Linear Regression
Data split into training and testing sets
Model trained to predict sales based on marketing spend


📈 Model Evaluation

Evaluation metrics used:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score

📌 The model demonstrates strong predictive capability, indicating that marketing spend is a reliable indicator of sales.


💡 Business Insights
📺 TV Ads drive the highest sales impact
📻 Radio Ads contribute moderately
📰 Newspaper Ads show minimal ROI

👉 Businesses should prioritize TV and Radio channels for better returns.

🛠️ Tech Stack
Python
Pandas – Data manipulation
NumPy – Numerical operations
Matplotlib / Seaborn – Data visualization
Scikit-learn – Machine learning
