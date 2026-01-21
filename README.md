# Movie Rating Predictor

This project predicts movie rating ranges based on user reviews using a machine learning model trained on IMDb movie review data.

## Overview
- Trains a text classification model on IMDb movie reviews
- Predicts whether a review is positive or negative
- Maps sentiment to a movie rating range (1–2 ⭐ or 4–5 ⭐)

## Dataset
- **IMDb Dataset of 50K Movie Reviews**
- Source: Kaggle  
- Dataset is accessed directly within the Kaggle environment and is not included in this repository.

## Approach
1. Cleaned raw review text (lowercasing, removing HTML tags and symbols)
2. Converted text to numerical features using TF-IDF
3. Trained a Naïve Bayes classifier for sentiment prediction
4. Mapped predicted sentiment to a movie rating range

## Technologies Used
- Python
- Scikit-learn
- NLTK
- Pandas

## How to Run
This project was developed and trained using Kaggle notebooks.

To run:
1. Open the notebook in Kaggle
2. Attach the IMDb dataset from Kaggle
3. Run cells sequentially

## Sample Output
Input Review:
> "The movie had great visuals but the story was weak"

Predicted Rating:
> **4–5 ⭐** or **1–2 ⭐** depending on sentiment
