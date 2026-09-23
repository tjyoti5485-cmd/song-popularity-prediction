# Song Popularity Prediction

This project predicts whether a song is a hit or non-hit using audio features from the Kaggle Song Popularity Dataset.

## Workflow

- Exploratory data analysis
- Missing-value and duplicate checks
- Outlier inspection
- Feature engineering
- Creation of `duration_min`
- Creation of `mood_index`
- Median-based `is_hit` classification
- 80/20 stratified train-test split
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- LightGBM

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Dataset

https://www.kaggle.com/datasets/yasserh/song-popularity-dataset
