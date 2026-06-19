# Sentiment Analysis — Legal Notice Classifier
*SAP ID:* 67340

## Project Overview
Multi-class text classification on legal notices using ML.
Dataset: 600 samples, 3 classes (Contract Dispute, IP Claim, Regulatory Compliance)

## Model Results
| Model | Accuracy | F1 (macro) |
|-------|----------|------------|
| Logistic Regression + BoW | 100% | 100% |
| Logistic Regression + TF-IDF | 100% | 100% |
| Naive Bayes + BoW | 100% | 100% |
| Naive Bayes + TF-IDF | 100% | 100% |

## EDA Results
- 600 samples, 3 balanced classes (200 each)
- Average notice length: 111 words

## MLflow
- 11 total runs logged
- 7 hyperparameter experiments (C values)
- Best C = 1.0

## Tools Used
Python, scikit-learn, MLflow, Google Colab
## EDA and Preprocessing
- Text cleaning: HTML removal, lowercase, punctuation removal
- Stopword filtering (custom list)
- BoW and TF-IDF feature extraction (max 5000 features)
