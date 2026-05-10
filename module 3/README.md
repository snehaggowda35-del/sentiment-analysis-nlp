# Module 3 – Naive Bayes Classifier

## Objective
The objective of this module is to build and train a Naive Bayes machine learning classifier for sentiment prediction.

---

## Description
This module implements a custom Naive Bayes classifier for classifying product reviews into:
- Positive
- Negative
- Neutral

---

## Tasks Performed

### 1. Data Splitting
The dataset was divided into:
- Training data
- Testing data

### 2. Custom Naive Bayes Class
A custom classifier was implemented using:
- Word frequency counts
- Class probabilities
- Laplace smoothing

### 3. Model Training
The classifier was trained using processed review text and sentiment labels.

### 4. Vocabulary Building
A vocabulary set was created from all unique words in the dataset.

### 5. Sentiment Prediction
The trained model predicted sentiment labels for unseen reviews.

### 6. Model Evaluation
Performance was evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix

### 7. Error Analysis
Common prediction challenges identified:
- Mixed sentiments
- Ambiguous short reviews
- Rare word occurrences

---

## Technologies Used
- Python
- Scikit-learn Metrics
- NLTK

---

## Output
The model successfully classified reviews into sentiment categories with good prediction accuracy.

---

## Conclusion
This module successfully implemented a machine learning based sentiment classifier using the Naive Bayes algorithm.