# Sentiment Analysis Project using Machine Learning
This project serves as an example implementation of sentiment analysis using machine learning techniques. The goal of the project is to create a model capable of classifying text reviews into positive and negative sentiments.
#### Based on this data, I achieved an accuracy of 87%, suggesting a high likelihood of correctly classifying customer inquiries eligible for discounts or other benefits.
## Project Description
The project includes the following stages:

- Data Preparation: The initial stage involves loading data from the Data.csv file. This file contains text reviews and their corresponding sentiment labels.

- Data Preprocessing: Text reviews undergo preprocessing, including converting to lowercase, removing URLs, HTML tags, punctuation, stop words, and stemming.

- Text Vectorization: Processed texts are transformed into a numerical format using vectorization (CountVectorizer).

- Model Training: Two models are considered in the project: Logistic Regression and Bernoulli Naive Bayes. Their performance is evaluated on the training data.

- Model Evaluation and Comparison: Models are evaluated on the test data, and their results are compared to determine which model performs better in sentiment analysis.

- Hyperparameters (Optional): Hyperparameters for Logistic Regression are tuned using GridSearchCV, but considering runtime and marginal performance improvement.

- User Testing Interface: The project provides a simple interface that allows users to input their custom text reviews and receive predicted sentiments.
## Note:

This description provides an overview of the project. If necessary, you can add more detailed information, results and conclusions from data analysis and experiments with models.
## Author
The author of this project: Aleksandr Loginov   https://github.com/LoginovAM-ds
## Connection
If you have any questions or suggestions, feel free to contact me via a.loginov.ds@gmail.com or https://www.facebook.com/profile.php?id=100074840106705.