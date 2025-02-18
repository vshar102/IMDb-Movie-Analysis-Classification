# IMDb-Movie-Analysis-Classification

# Overview
This project involves performing sentiment analysis on an IMDb movie reviews dataset to classify reviews into three categories: Negative, Neutral, and Positive. The goal was to develop a model that could predict the sentiment of a movie review based on textual data and to gain insights into movie ratings, genres, and review patterns. Python was used for data preprocessing, machine learning model implementation, and evaluation.

# Dataset Features:
Poster: Image link or identifier
Title: Movie title
Year: Release year
Certificate: Age rating
Duration (min): Duration of the movie in minutes
Genre: Movie genre (e.g., Drama, Comedy, Action)
Rating: IMDb rating (e.g., 8.2)
Metascore: Critic score
Director: Director of the movie
Cast: Cast involved in the movie
Votes: Number of votes received for the movie
Description: Movie description
Review Count: Number of reviews for the movie
Review Title: Title of the review
Review: Textual content of the review

# Process:
# Data Preprocessing:
Cleaned the dataset by handling missing values and normalizing text data.
Used techniques such as tokenization, stop-word removal, and lemmatization to preprocess the textual data in the reviews.

# Exploratory Data Analysis (EDA):
Visualized the distribution of movie ratings, genres, and other relevant features using heatmaps and histograms.
Examined the correlation between various features such as ratings, genres, and review scores.

# Sentiment Analysis:
Utilized NLTK's Vader sentiment analyzer to assign sentiment scores to the reviews.
Categorized reviews into Negative, Neutral, and Positive based on the sentiment score.

# Machine Learning Models:
Implemented four different classification models to predict sentiment:
Naive Bayes
Logistic Regression
Support Vector Machine (SVM)
Random Forest
Evaluated the models using various metrics like accuracy, confusion matrix, and classification reports.

# Model Evaluation:
Achieved the highest accuracy score of 83.55% with the Logistic Regression model.
The models were evaluated for precision, recall, and F1-score, with performance metrics demonstrating the models' ability to accurately classify sentiment.

# Visualization:
Employed data visualization techniques such as heatmaps and histograms to represent the sentiment distribution across genres and ratings.
Displayed the sentiment analysis results with clear visual representations for easier interpretation.

# Key Findings:
Sentiment Trends: Identified sentiment patterns based on movie genres, where certain genres like Drama tended to have a higher percentage of Positive reviews.
Model Performance: Logistic Regression outperformed other models in terms of accuracy, but Naive Bayes and SVM also showed competitive results.

# Tools & Libraries:
Python: Main programming language for data processing and model implementation.
Pandas: Used for data manipulation and analysis.
NLTK: Used for text preprocessing and sentiment analysis.
Scikit-learn: Machine learning library used for model implementation and evaluation.
Matplotlib/Seaborn: Used for data visualization.

# Conclusion:
This project showcases expertise in sentiment analysis, machine learning, and data visualization. The developed models can be used to predict the sentiment of movie reviews, which is useful for understanding user opinions and trends in the media and entertainment industry. The ability to classify and analyze large volumes of textual data opens doors for more automated systems in content curation, recommendation engines, and user engagement metrics.
