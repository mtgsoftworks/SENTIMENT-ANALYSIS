# SENTIMENT-ANALYSIS

# Technical Documentation for Sentiment Analysis of Amazon Reviews
#### 1. Introduction
This documentation provides a detailed explanation of a sentiment analysis project aimed at analyzing Amazon reviews for a company named Kozmos, which focuses on home textiles and casual clothing. The goal is to label the reviews based on their sentiment and build a classification model to predict future reviews' sentiments.

#### 2. Business Problem
Kozmos aims to enhance its products and increase sales by analyzing customer reviews on Amazon. By understanding customer sentiments and addressing complaints, the company can improve product features and customer satisfaction.

#### 3. Dataset Description
The dataset consists of reviews for a specific product group and includes the following variables:

Review: The review content.
Title: The title of the review, which is a short comment.
Helpful: The number of people who found the review helpful.
Star: The star rating given to the product.
The dataset is provided in an Excel file named amazon.xlsx.

#### 4. Tasks Overview
The project involves the following tasks:

Text Preprocessing: Cleaning and preparing the text data for analysis.
Text Visualization: Visualizing the frequency of words in the reviews.
Sentiment Modeling: Labeling reviews based on their star ratings and building a classification model.
Model Evaluation: Evaluating the performance of the classification model.
#### 5. Detailed Steps
5.1. Import Necessary Libraries
The following libraries are used in this project:

#### pandas
#### numpy
#### re
#### string
#### sklearn
#### matplotlib
#### seaborn
#### nltk

#### 5.3. Text Preprocessing
Preprocess the text data in the Review column to prepare it for analysis. The preprocessing steps include:

### 1-) Converting text to lowercase.
### 2-) Removing punctuation.
### 3-) Removing numbers.
### 4-) Removing stopwords.
### 5-) Lemmatizing words.


#### Text Visualization
Calculate the frequency of words in the Processed_Review column and visualize the top 20 most common words using a bar plot.

#### 5.5. Sentiment Modeling
Label the reviews as positive, neutral, or negative based on the star rating. Split the data into training and testing sets, vectorize the text data, and train a logistic regression model.

#### 5.6. Model Evaluation
Evaluate the model's performance by calculating the accuracy, printing a classification report, and displaying a confusion matrix.

#### 6. Conclusion
This project involves analyzing Amazon reviews for Kozmos to understand customer sentiment and improve product offerings. By preprocessing text data, visualizing word frequencies, building a sentiment classification model, and evaluating its performance, valuable insights can be derived to aid business decisions. The logistic regression model provides a robust tool for predicting the sentiment of new reviews based on the patterns learned from historical data.
