# Phishing Email Detection Using Machine Learning

## Project Overview

This project implements a machine-learning-based phishing email detection system using Natural Language Processing (NLP).

The system analyses email text and classifies messages as either:

- Safe Email
- Phishing Email

The project demonstrates how machine learning can be applied to cybersecurity to assist in identifying potentially malicious email messages.

## Objectives

The objectives of this project were to:

- Clean and prepare an email dataset.
- Perform exploratory analysis of the dataset.
- Convert email text into numerical features using TF-IDF.
- Train a machine-learning classification model.
- Evaluate model performance.
- Test the model using new email messages.
- Develop a simple phishing email detection interface.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Natural Language Processing (NLP)
- TF-IDF

## Dataset

The dataset contains labelled email messages classified as either safe or phishing.

The dataset contains:

- **18,650 email records**
- **11,322 Safe Emails**
- **7,328 Phishing Emails**

## Project Methodology

```text
Email Dataset
     ↓
Data Exploration
     ↓
Data Cleaning
     ↓
Text Preprocessing
     ↓
Train/Test Split
     ↓
TF-IDF Feature Extraction
     ↓
Logistic Regression
     ↓
Model Evaluation
     ↓
Phishing Email Prediction

## Model Performance

The trained model achieved:

**97.43% Accuracy**

### Classification Performance

| Class | Precision | Recall | F1-Score |
|---|---:|---:|---:|
| Safe Email | 0.97 | 0.99 | 0.98 |
| Phishing Email | 0.98 | 0.96 | 0.97 |

## Confusion Matrix

The model correctly classified:

- **2,164 Safe Emails**
- **1,253 Phishing Emails**

The model incorrectly classified:

- **32 Safe Emails as Phishing**
- **58 Phishing Emails as Safe**

The false negatives are particularly important from a cybersecurity perspective because they represent phishing messages that were not detected.

## Phishing Detection Tool

The project also includes an interactive component that allows a user to enter an email message and receive a prediction.

Example:

```text
URGENT! Your account has been suspended.
Click the link below to verify your password immediately.

Result: PHISHING EMAIL
Confidence: 91.85%


Security Relevance

This project demonstrates practical application of:

Cybersecurity
Machine Learning
Natural Language Processing
Phishing Detection
Security Automation
Data Analysis
Threat Detection
Limitations

The model is dependent on the training dataset and may not detect every type of phishing email.

Attackers can modify wording, URLs, sender information, and message structure to evade detection.

The model should therefore be considered an analytical tool rather than a replacement for a complete email security solution.

Future Improvements

Future improvements could include:

URL reputation analysis
Email header analysis
Sender reputation checks
Attachment analysis
Domain intelligence
Integration with SIEM platforms
Real-time email analysis
Web-based deployment
Additional machine-learning algorithms
Larger and more diverse datasets
Project Evidence

Screenshots of the model evaluation, confusion matrix, and phishing detection tool are included in the screenshots directory.

Author

Mulalo Tharaga

Cybersecurity | Data & IT | Machine Learning