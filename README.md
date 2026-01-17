![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Natural Language Processing Challenge

## Introduction

Learning how to process text is a skill required for Data Scientists. 
In this project, you will put these skills into practice to identify whether a news headline is real or fake news.

## Project Overview

In the file `dataset/training_data.csv` you will find dataset containing news headlines and their tags: 
0, if the headline is fake news, and, 1, if the headline is real news. 

Your goal is to build a classifier that is able to distinguish between the two.

Once you have a classifier built, then use it to predict the labels for `dataset/testing_data.csv`. Generate a new file
where the label `2` has been replaced by `0` (fake) or `1` (real) according to your model. Please respect the original file format, 
do not include extra columns, and respect the column separator. 


## Guidance
Like in a real life scenario, you are able to make your own choices and text treatment. 
Use the techniques you have learned and the common packages to process this data and classify the text.

## Deliverables

1. **Python Code:** Provide well-documented Python code that conducts the analysis.
2. **Predictions:** A csv file in the same format as `testing_data.csv` but with the predicted labels (0 or 1)
3. **Accuracy estimation:** Provide the teacher with your estimation of how your model will perform.
4. **Presentation:** You will present your model in a 10-minute presentation. Your teacher will provide further instructions.





# Project | NLP - text classification

## Task Description

You will build a text-classification model to distinguish real news from fake news.

## instructions
   
   
    *   Split the training.csv file into training and test sets.
    *   Apply text preprocessing (lowercasing, tokenization, removing stop words and punctuation, etc.).
    *   Create text vectors using Bag of Words or TF-IDF, and experiment with their parameters (n-grams, max_df, min_df, max_features, custom tokenizer, etc.).
    *   Try different classifiers such as Logistic Regression, Random Forest, XGBoost, SVM, MultinomialNB, etc.
    *   Perform hyperparameter tuning.
    *   Compare all models and choose the best-performing one.
    *   Use your best model to predict the labels in testing.csv, replacing the value 2 in the first column with your predicted class (0 or 1).


## Deliverables
    *   Your Jupyter NotebookA PPTX presentation
    *   The updated testing.csv file containing your best model’s predictions
