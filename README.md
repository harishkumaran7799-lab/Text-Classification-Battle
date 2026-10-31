# Text Classification Battle – SMS Spam Detection

## Project Description
This project compares four machine learning algorithms for classifying SMS messages as Ham (legitimate) or Spam (unwanted).

## Dataset
UCI SMS Spam Collection Dataset

- Total messages: 5,572
- Ham messages: 4,825
- Spam messages: 747

## Algorithms
1. Decision Tree
2. K-Nearest Neighbours (KNN)
3. Support Vector Machine (SVM)
4. Multinomial Naïve Bayes

## Technologies Used
- Python
- Google Colab
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## Feature Extraction
TF-IDF (Term Frequency–Inverse Document Frequency).

## Evaluation Metrics
Accuracy, Precision, Recall and F1-score.

## What-if Experiment
Compared TF-IDF Unigrams (1,1) with Unigrams + Bigrams (1,2).

## Best Performing Model
SVM with Unigrams + Bigrams.

- Accuracy: 98.57%
- Precision: 98.54%
- Recall: 90.60%
- F1-score: 94.41%

## Conclusion
SVM with Unigrams + Bigrams achieved the highest F1-score among the four tested classifiers.
