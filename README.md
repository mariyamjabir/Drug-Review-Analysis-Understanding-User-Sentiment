# Drug-Review-Analysis-Understanding-User-Sentiment

## Introduction

In the era of information and user-generated content, online drug reviews provide valuable insights into the experiences and perceptions of individuals using pharmaceutical products. This project presents an analysis of drug reviews from a dataset obtained through online platform named UCI Machine Learning Repository. The goal is to gain a comprehensive understanding of user sentiment, identify prominent drugs, and explore the prevalence of various medical conditions.

## Data Collection

The dataset used in this analysis was collected from online drug review platforms and is stored in a structured format. The dataset includes information on drug names, conditions, reviews, and user ratings. The dataset was loaded into a Pandas DataFrame for further exploration and analysis.

## Objective

- The primary objective of this analysis is to extract meaningful insights from the drug review dataset.
- To develop a machine learning model for sentiment analysis in medical reviews to predict patient conditions.
- The project focuses on five specific medical conditions: birth control, depression, pain, anxiety, and acne.

## Methodology

### Exploratory Data Analysis (EDA)

- Visualize the distribution of ratings.
- Explore the word cloud for drug names to identify frequently mentioned drugs.
- Analyze the top drugs with a perfect rating of 10/10.
- Investigate the prevalence of medical conditions through bar plots.

### Feature Engineering

- Categorize ratings into positive and negative sentiments.
- Create additional features to enhance the dataset for modeling.

### Data Preprocessing

- Handle missing values in the dataset.
- Scale numerical features for uniformity.
- Select a subset of conditions for focused analysis.

### Text Processing

- Tokenize, stem, lemmatize, and remove stopwords from review texts for natural language processing.

### Model Selection

- Utilize machine learning models, including Random Forest and Naive Bayes, to predict medical conditions based on reviews.
- Train and evaluate models on the preprocessed data.

## Model Evaluation Metrics

Evaluate model performance using the following metrics:

- **Accuracy:** Measure the overall correctness of the model predictions.
- **Precision:** Assess the precision of the model in correctly predicting positive and negative conditions.
- **Recall:** Examine the ability of the model to capture positive and negative conditions.
- **F1 Score:** Balance between precision and recall, providing a comprehensive evaluation of model performance.
