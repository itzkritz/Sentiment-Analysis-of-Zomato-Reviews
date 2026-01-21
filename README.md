# Sentiment-Analysis-of-Zomato-Cafe-Reviews
This project involves analyzing customer feedback from Zomato to determine the overall sentiment (positive, negative, or neutral) toward various restaurants.

# Project Overview
This project focuses on performing sentiment analysis on customer reviews from Zomato. By analyzing text feedback, the project aims to classify customer emotions as positive, negative, or neutral. This analysis provides restaurant owners with insights into customer satisfaction and highlights areas for improvement based on real-world data.

# Dataset Description
The project utilizes a dataset of approximately 775 Zomato reviews from various cities, including Ahmedabad, Mumbai, Chandigarh, and others. Each entry includes:

Restaurant Name

Overall Rating

Cuisine

Approximate Cost for Two

Location (City)

Customer Review Text

link of kaggle dataset- https://www.kaggle.com/datasets/juhibhojani/zomato-cafe-reviews

# Methodologies
The project explores two main approaches for sentiment classification:

# 1. Sentiment Analysis using NLTK (VADER)

Exploratory Data Analysis (EDA): Performed initial analysis to visualize the distribution of reviews by star rating (ranging from 1 to 5 stars).


VADER Tool: Utilized the NLTK library's VADER (Valence Aware Dictionary and sEntiment Reasoner) to extract polarity scores (negative, neutral, positive, and compound) from each review.


Validation: Compared the VADER "compound" scores against the original Zomato ratings to assess accuracy and trends in sentiment.

# 2. Sentiment Analysis using Transformers
Pre-trained Models: Implemented a modern approach using Hugging Face Transformers.

Sentiment Pipeline: Used a pre-trained sentiment analysis pipeline to classify reviews with high precision, providing both categorical labels (e.g., POSITIVE, NEGATIVE) and confidence scores.

# Key Findings
The project successfully demonstrates the correlation between user ratings and computed sentiment scores.

The Transformer-based model provides a more nuanced understanding of complex reviews compared to rule-based lexicon methods like VADER.

Visualization of "Compound Scores" by star ratings highlights how customer sentiment shifts across different satisfaction levels.

# Technologies Used
Python

Pandas & NumPy for data manipulation

Matplotlib & Seaborn for data visualization

NLTK (VADER) for rule-based sentiment analysis

Hugging Face Transformers for deep learning-based analysis
