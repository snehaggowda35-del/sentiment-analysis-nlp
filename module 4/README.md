# Module 4 – Information Retrieval System

## Objective
The objective of this module is to retrieve relevant product reviews using TF-IDF scoring and information retrieval techniques.

---

## Description
This module implements an information retrieval pipeline capable of:
- Preprocessing user queries
- Predicting sentiment
- Retrieving similar reviews
- Ranking documents using TF-IDF

---

## Tasks Performed

### 1. Inverted Index Creation
An inverted index was built for fast word-based document retrieval.

### 2. TF Calculation
Term Frequency was calculated based on word occurrence within documents.

### 3. IDF Calculation
Inverse Document Frequency was calculated to determine word importance.

### 4. TF-IDF Scoring
TF-IDF scores were generated for ranking review relevance.

### 5. User Review Processing
The system accepts custom product reviews from the user.

### 6. Sentiment Prediction
The trained Naive Bayes classifier predicts:
- Positive
- Negative
- Neutral

### 7. Top Review Retrieval
Top 5 relevant reviews were retrieved based on TF-IDF similarity scores.

### 8. Query Expansion
WordNet-style synonym expansion was implemented.

Example:
good → great, excellent, nice

### 9. Precision@5
Average Precision@5 metric was calculated to evaluate retrieval quality.

---

## Technologies Used
- Python
- TF-IDF
- Information Retrieval Techniques
- NLTK

---

## Output
The system successfully retrieved relevant product reviews and predicted sentiment for user-entered queries.

---

## Conclusion
This module successfully implemented an NLP-based information retrieval system integrated with sentiment analysis.