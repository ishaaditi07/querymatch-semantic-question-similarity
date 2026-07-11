# QueryMatch – Semantic Question Similarity Detection

## Overview

QueryMatch is a Natural Language Processing (NLP) project that determines whether two questions are semantically similar. The project combines text preprocessing, handcrafted feature engineering, Bag-of-Words vectorization, and machine learning models to identify duplicate question pairs.

The project includes data preprocessing, feature engineering, model training, evaluation, and a Streamlit web application for real-time predictions.

---

## Features

* Text preprocessing and normalization
* Bag-of-Words (BoW) vectorization
* Handcrafted feature engineering
* Fuzzy string matching
* Random Forest and XGBoost models
* Confusion Matrix evaluation
* Interactive Streamlit application

---

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* NLTK
* FuzzyWuzzy
* Streamlit
* Matplotlib
* Seaborn

---

## Project Structure

```text
querymatch-semantic-question-similarity/

├── bow-with-preprocessing-and-advanced-features.ipynb
└── streamlit-app/
    ├── app.py
    ├── helper.py
    ├── requirements.txt
    ├── Procfile
    ├── setup.sh
    └── readme.txt
```

---

## Machine Learning Pipeline

1. Load the dataset
2. Perform text preprocessing
3. Extract handcrafted similarity features
4. Generate Bag-of-Words vectors
5. Train machine learning models
6. Evaluate model performance
7. Predict semantic similarity using the Streamlit application

---

## Models Used

* Random Forest Classifier
* XGBoost Classifier

---

## Dataset

This project uses the **Quora Question Pairs** dataset available on Kaggle.

https://www.kaggle.com/c/quora-question-pairs

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/ishaaditi07/querymatch-semantic-question-similarity.git
```

Install dependencies:

```bash
pip install -r streamlit-app/requirements.txt
```

Launch the Streamlit application:

```bash
cd streamlit-app
streamlit run app.py
```

---

## Future Improvements

* TF-IDF vectorization
* Transformer-based embeddings (BERT/Sentence-BERT)
* Hyperparameter tuning
* ROC-AUC and F1-score comparison
* Docker containerization
* Cloud deployment

---

## Author

**Isha Aditi**
