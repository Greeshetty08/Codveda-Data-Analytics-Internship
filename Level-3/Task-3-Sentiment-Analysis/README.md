# Sentiment Analysis using Natural Language Processing (NLP)

## Objective

The objective of this project is to analyze textual data and classify sentiments into Positive, Negative, and Neutral categories using Natural Language Processing (NLP) techniques and Machine Learning.

## Tools Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* WordCloud

## Dataset

The dataset contains social media posts along with sentiment labels and additional metadata such as platform, hashtags, likes, retweets, and timestamps.

### Features Used

* Text
* Sentiment

## Data Preprocessing

* Loaded the sentiment dataset.
* Selected relevant text and sentiment columns.
* Prepared textual data for machine learning using TF-IDF Vectorization.

## Exploratory Analysis

### Sentiment Distribution

* Visualized the distribution of Positive, Negative, and Neutral sentiments.
* Identified the overall sentiment trend within the dataset.

### Word Cloud

* Generated a Word Cloud to visualize the most frequently occurring words in the text data.

## Machine Learning Model

### TF-IDF Vectorization

* Converted text data into numerical feature vectors.

### Naive Bayes Classifier

* Trained a Multinomial Naive Bayes model on the processed text data.
* Predicted sentiment labels on the test dataset.

## Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1 Score
* Classification Report

## Visualizations

* Sentiment Distribution Chart
* Word Cloud
* Classification Results

## Results

The sentiment classification model successfully categorized text data into Positive, Negative, and Neutral classes. The analysis provided insights into public sentiment and demonstrated the effectiveness of NLP techniques for text classification.

## Conclusion

This project demonstrates the application of Natural Language Processing and Machine Learning for sentiment analysis. The combination of TF-IDF Vectorization and Naive Bayes Classification provides an effective approach for analyzing textual sentiment data.

