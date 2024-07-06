# Fake-News-Prediction

This project aims to predict whether a news article is real or fake using Natural Language Processing (NLP) techniques and a Logistic Regression model. The dataset used contains various news articles labeled as either real or fake.

## **Overview**
In this project, we preprocess the text data from news articles, vectorize it using TF-IDF, and train a Logistic Regression model to classify the articles as real or fake.
The steps involved are:

**Data Preprocessing**

**Text Vectorization**

**Model Training**

**Evaluation**

**Making Predictions**

## **Dataset**

The dataset used in this project can be found here.

[Train Dataset](https://www.kaggle.com/c/fake-news/data?select=train.csv)

## **Installation**

To set up this project locally, follow these steps:

1. Clone the repository:

```bash

 https://github.com/YandapalliChinni/Fake-News-Prediction.git

 cd Fake-News-Prediction

```

2. Install the required dependencies:

``` bash

pip install -r requirements.txt
```

3. Download the dataset and place it in the project directory.

## **Challenges**

One of the main challenges was dealing with missing values in the dataset. We addressed this by filling missing values with empty strings. Another challenge was text preprocessing, which involved stemming and removing stopwords to improve model performance.

## **Results**
The model achieved an accuracy of:

**Training data**: 98.66%

**Test data**: 97.91%
