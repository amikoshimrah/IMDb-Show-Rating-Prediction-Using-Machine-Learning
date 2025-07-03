# IMDb-Show-Rating-Prediction-Using-Machine-Learning
This project focuses on predicting IMDb ratings for TV shows and movies using machine learning techniques. The dataset includes rich metadata such as title, year, genre, cast, crew, votes, duration, and reviews.

🔍 Objective
To build a regression model that can predict IMDb ratings based on relevant show features and analyze which factors most influence viewer ratings.

🧰 Tools & Technologies
Languages & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn
ML Algorithms: Linear Regression, Decision Trees, Random Forest, XGBoost
Visualization & EDA: Correlation matrix, scatter plots, genre encoding
Data Processing: Feature cleaning, transformation, and encoding

📊 Workflow
Data Cleaning: Removed duplicates, handled missing values, and converted text fields (e.g., duration, votes) to numerical types.
Feature Engineering: Converted genres into one-hot encoded features and created a new column for duration in minutes.
Exploratory Data Analysis (EDA): Analyzed correlations and created visualizations to understand data relationships.
Model Building & Evaluation: Trained multiple models to predict IMDb ratings and evaluated their performance using regression metrics.

📁 Notable Features
Custom function to parse and convert runtime (e.g., "2h 30m") into total minutes.
Genre multi-label transformation for enhanced model input.
Clear EDA to justify model decisions.
