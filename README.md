# machine-learning-portfolio
🎓 Indikraft Machine Learning Internship: Final Portfolio
Intern Name: KRISH

Role: Machine Learning Intern

Date: 05/12/2025

📘 Executive Summary
This notebook represents the culmination of my internship at Indikraft. Over the course of this program, I have successfully designed, built, and deployed 5 Machine Learning & Data Science projects, ranging from Natural Language Processing (NLP) to Regression Analysis and Unsupervised Clustering.

🛠️ Technical Toolkit
Throughout these projects, I utilized the following technologies:

Python: Core programming logic.
Scikit-Learn: Model training (Regression, K-Means).
Pandas & NumPy: Data manipulation and feature engineering.
Seaborn & Matplotlib: Advanced data visualization.
TextBlob: Sentiment analysis and NLP.

🚀 Project 1: Product Rating Predictor (NLP + Regression)
📌 Problem Statement
E-commerce platforms receive thousands of reviews daily. Manually reading them to assign a star rating is impossible. The goal of this project was to build an AI that can read text and predict a numeric rating (1-5).

⚙️ Methodology
Data Ingestion: Created a dataset of customer reviews.
Vectorization (TF-IDF): Computers cannot understand words. I used Term Frequency-Inverse Document Frequency to convert text into mathematical vectors.
Model Training: Trained a Linear Regression model to find the correlation between specific words (e.g., "Good", "Bad") and the rating score.

🏠 Project 2: Price Predictor
📌 Problem Statement
Predicting property prices is complex because raw data is often not "model-ready." A computer sees the year "1990" as a number, not an age.

⚙️ Feature Engineering Approach
This project focused on Feature Engineering—the art of creating new data from existing data.

Transformation: Converted Year_Built → House_Age (2025 - Year).
Encoding: Converted categorical locations ('City', 'Rural') into binary inputs (0s and 1s) using One-Hot Encoding.

🛒 Project 3: Product Clustering (Unsupervised Learning)
📌 Problem Statement
In recommendation systems, we often don't have labeled data (we don't know which products are "Premium" vs "Budget"). We need the AI to discover these groups automatically.

⚙️ Methodology
I utilized K-Means Clustering, an unsupervised algorithm.

Scaling: Standardized Price ($2000) and Review (4.5) to the same scale so Price didn't dominate the math.
Clustering: The algorithm grouped products into 3 distinct clusters based on similarities.

📊 Project 4: Data Visualization
📌 Problem Statement
Raw data in spreadsheets is difficult to interpret. The goal was to use Data Visualization to extract business insights regarding Seasonality and Category Performance.

⚙️ Visualization Strategy
Seaborn was used for statistical styling.
Matplotlib Subplots allowed for a dashboard layout.
Insights: The visualizations revealed a strong correlation between the holiday season (Dec) and peak sales.

🗣️ Project 5: Review Analysis (NLP)
📌 Problem Statement
To further enhance review analysis, I built a Sentiment Analyzer using Natural Language Processing (NLP).

⚙️ Methodology
Using the TextBlob library, the system assigns a Polarity Score to text:

> 0: Positive Sentiment
< 0: Negative Sentiment
0: Neutral
