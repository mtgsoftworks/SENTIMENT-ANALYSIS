# Sentiment Analysis for Amazon Reviews

## 1. Introduction
This project involves sentiment analysis of Amazon reviews, focusing on home textiles and casual clothing. The objective is to classify reviews by sentiment, allowing for enhanced product insights and sentiment prediction for future reviews.

---

## 2. Business Problem
By analyzing customer reviews, the company aims to:
- Improve product features and customer satisfaction.
- Increase sales by addressing customer feedback and identifying areas of improvement.

---

## 3. Dataset Description
The dataset, provided in an Excel file (`amazon.xlsx`), contains reviews for specific product groups with the following fields:

- **Review**: Content of the review.
- **Title**: Short title or comment for the review.
- **Helpful**: Number of users who found the review helpful.
- **Star**: Star rating given to the product.

---

## 4. Project Workflow
The project includes the following key steps:

1. **Text Preprocessing**: Prepare text data for analysis by cleaning and structuring.
2. **Text Visualization**: Visualize word frequency in reviews to identify common themes.
3. **Sentiment Modeling**: Label and classify reviews based on sentiment.
4. **Model Evaluation**: Evaluate the model's performance.

---

## 5. Detailed Steps

### 5.1. Import Necessary Libraries
The following libraries are used in this project:

- `pandas`
- `numpy`
- `re`
- `string`
- `sklearn`
- `matplotlib`
- `seaborn`
- `nltk`

### 5.2. Text Preprocessing
To prepare the `Review` text data for analysis, the following preprocessing steps are applied:

1. Convert text to lowercase.
2. Remove punctuation.
3. Remove numbers.
4. Remove stopwords.
5. Lemmatize words.

---

### 5.3. Text Visualization
Calculate the frequency of words in the processed reviews and create a bar plot to display the top 20 most common words.

---

### 5.4. Sentiment Modeling
1. **Label Reviews**: Label each review as positive, neutral, or negative based on its star rating.
2. **Data Splitting**: Divide the data into training and testing sets.
3. **Vectorization**: Vectorize the text data.
4. **Model Training**: Train a logistic regression model to classify sentiment.

---

### 5.5. Model Evaluation
Evaluate the model’s performance by:

- Calculating accuracy.
- Printing a classification report.
- Displaying a confusion matrix.

---

## 6. Conclusion
This project delivers insights into customer sentiment on Amazon, providing actionable feedback for product improvement. By preprocessing text data, visualizing key words, building a sentiment classification model, and evaluating its performance, the company gains a valuable tool for predicting sentiment in future reviews. The logistic regression model serves as a robust predictor based on historical data patterns.

--- 
