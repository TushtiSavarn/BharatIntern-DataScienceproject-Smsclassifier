# Project 1 
# SMS Spam Classifier

This project aims to classify SMS messages as either spam or ham (not spam) using machine learning algorithms. The project involves several steps, including data cleaning, exploratory data analysis (EDA), text preprocessing, model building, evaluation, and deployment.

## Steps:

### 1. Data Cleaning:
- Load the SMS dataset.
- Remove unnecessary columns.
- Encode the target variable (spam/ham) using LabelEncoder.
- Remove duplicate entries.

### 2. Exploratory Data Analysis (EDA):
- Visualize the distribution of spam and ham messages using a count plot.
- Calculate and visualize additional statistics such as the number of characters, words, and sentences in each message.

### 3. Text Preprocessing:
- Tokenize the text.
- Convert text to lowercase.
- Remove stopwords and punctuation.
- Apply stemming to reduce words to their root form.

### 4. Model Building:
- Use TF-IDF Vectorizer to convert text data into numerical features.
- Split the dataset into training and testing sets.
- Train multiple classification models, including Multinomial Naive Bayes, Extra Trees Classifier, Voting Classifier, and Stacking Classifier.

### 5. Model Evaluation:
- Evaluate the performance of each model using accuracy and precision metrics.
- Choose the best-performing model based on evaluation results.

### 6. Model Improvement:
- Experiment with different classifiers and hyperparameters to improve model performance.

### 7. Deployment:
- Save the best-performing model and TF-IDF Vectorizer using pickle for future use.
- Deploy the model using a web application framework like Flask or Streamlit.

These project was developed by Tushti Savarn.
Dataset source(project 1): https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
