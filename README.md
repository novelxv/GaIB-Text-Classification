# Emotion Classification End-to-End Machine Learning

This notebook is designed for the selection process of GalB Lab Assistant. It contains code for an end-to-end machine learning pipeline to classify emotions from text (emotion classification).

## Dataset

- The main dataset used is the **Indonesian Twitter Emotion Dataset** obtained from [this repository](https://github.com/meisaputri21/Indonesian-Twitter-Emotion-Dataset).
- The datasets used in this project are:
  - `Twitter_Emotion_Dataset.csv`: Contains Indonesian tweets labeled with emotions.
  - `kamus_singkatan.csv`: A dictionary for common Indonesian abbreviations used on social media to assist in preprocessing.

## Contents

The notebook includes an end-to-end pipeline for emotion classification, starting from data loading, exploration, and preprocessing. Exploratory Data Analysis (EDA) is performed to visualize the distribution of emotions. The preprocessing step involves cleaning the data, expanding abbreviations, and preparing the text for machine learning. 

The text data is vectorized using **TF-IDF**, and a **Logistic Regression** model is trained for emotion classification. Model performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Author

- Name: Novelya Putri Ramadhani
- NIM: 13522096