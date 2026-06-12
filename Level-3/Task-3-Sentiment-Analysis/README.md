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
The sentiment classification model was trained using TF-IDF Vectorization and Multinomial Naive Bayes. Due to the large number of sentiment categories and limited samples per class, the model achieved modest predictive performance. However, the project successfully demonstrates the complete NLP workflow including text preprocessing, feature extraction, sentiment visualization, and sentiment classification.

## Conclusion

This project demonstrates the application of Natural Language Processing and Machine Learning for sentiment analysis. The combination of TF-IDF Vectorization and Naive Bayes Classification provides an effective approach for analyzing textual sentiment data.

