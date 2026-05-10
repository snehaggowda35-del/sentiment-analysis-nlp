# Module 1 – Language Model

## Objective
The objective of this module is to build a basic statistical language model using NLP techniques for sentiment analysis on e-commerce product reviews.

---

## Description
This module focuses on preprocessing text data and constructing unigram and bigram language models. It also calculates probability scores and perplexity to evaluate language understanding.

---

## Dataset Used
Dataset File:
`balanced_sentiment_dataset_900.csv`

The dataset contains:
- Positive reviews
- Negative reviews
- Neutral reviews

---

## Tasks Performed

### 1. Dataset Loading
The product review dataset was loaded using Pandas.

### 2. Text Preprocessing
The following preprocessing steps were applied:
- Lowercase conversion
- Removal of special characters
- Stopword removal
- Tokenization

### 3. Negation Handling
Negation words such as:
- not
- never
- cant
- didnt

were combined with the next word using:
`NOT_word`

Example:
not good → NOT_good

### 4. Train-Test Split
The tokenized data was divided into:
- Training set
- Testing set

### 5. Unigram Model
A unigram frequency model was created using word occurrence counts.

### 6. Bigram Model
Bigram probabilities were generated using adjacent word pairs.

### 7. Add-One Smoothing
Laplace smoothing was applied to avoid zero probability issues.

### 8. Perplexity Calculation
Perplexity was calculated to evaluate language model performance.

---

## Technologies Used
- Python
- Pandas
- NLTK
- Regular Expressions

---

## Output
The module successfully generated:
- Unigram frequencies
- Bigram probabilities
- Smoothed probabilities
- Perplexity score

---

## Conclusion
This module successfully implemented a statistical language model capable of understanding word sequence patterns in product reviews.