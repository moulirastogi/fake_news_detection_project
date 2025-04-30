# Fake News Detection using Machine Learning

## Overview

This repository contains a Jupyter notebook for a Fake News Detection project using machine learning techniques. 

## Prerequisites

Make sure you have the required libraries installed by running the following commands:

```bash
pip install pandas numpy matplotlib seaborn wordcloud nltk gensim plotly scikit-learn
```

## Contents

The notebook is divided into the following sections:

1. **Loading the Dataset**
   - Reads and loads the True and Fake news datasets from [Kaggle](https://www.kaggle.com/code/therealsampat/fake-news-detection).

2. **Setting up a target and merging datasets**
   - Adds a target column indicating whether the news is true (1) or fake (0).

3. **Checking the number of null values**
   - Identifies and handles null values in the dataset.

4. **Data Cleaning**
   - Removes stopwords and performs data cleaning.

5. **Exploratory Data Analysis (EDA)**
   - Analyzes and visualizes the distribution of true and fake news, most covered issues, word cloud and maximum word count in a title.

6. **Data Preprocessing**
   - Further cleans and prepares the data for model training.

7. **Model Building**
   - Utilizes three algorithms for training and evaluation:
      - Logistic Regression
      - Decision Tree Classifier
      - Random Forest Classifier

8. **Manual Testing**
   - Allows users to input news for manual testing and provides predictions from the trained models.


## Contributing

Feel free to contribute, provide feedback or report issues.
