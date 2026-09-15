# Sentiment-Analysis
# Emotion Classification using Machine Learning

## Overview

This project uses machine Learning to classify text comments into three emotions: **Anger, Fear, and Joy**.

The text is preprocessed and converted into numerical features using **TF-IDF**, followed by classification using **Naive Bayes** and **Support Vector Machine (SVM)**.

##  Workflow

* Text cleaning
* Tokenization
* Stopword removal
* Train-test split
* TF-IDF feature extraction
* Naive Bayes & SVM classification
* Model evaluation using Accuracy and F1-score
* Confusion matrix
* New text emotion prediction

##  Results

| Model       |   Accuracy |   F1 Score |
| ----------- | ---------: | ---------: |
| Naive Bayes |     89.98% |     89.98% |
| **SVM**     | **92.85%** | **92.84%** |

**Best Model: SVM**

## Technologies

* Python
* Pandas
* NLTK
* Scikit-learn
* Jupyter Notebook

##  Dataset

The dataset contains **5,937 text comments** categorized into:

* Anger
* Fear
* Joy

## Conclusion

SVM achieved the best performance with **92.85% accuracy** and **92.84% F1-score**, making it the preferred model for this emotion classification task.

