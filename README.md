#  Turkish News Text Classification with NLP and Machine Learning

This project focuses on automatically classifying Turkish news articles into different categories using Natural Language Processing (NLP), Machine Learning, and Deep Learning techniques.

The project was developed during the first semester of my third year in Software Engineering as part of a News Text Classification course project.

---

##  Objective

The goal of this project is to classify Turkish news articles into the following categories:

- Criminal
- Health
- Politic/Economic
- Sports
- Technology

The project compares multiple text representation methods and machine learning algorithms to evaluate their performance.

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Gensim
- Joblib

---

##  NLP Techniques

### Text Cleaning
- Lowercasing
- URL removal
- Special character filtering
- Duplicate removal
- Missing value removal
- Minimum text length filtering

### Leakage Prevention
- Removal of publisher names and metadata words
- Removal of category-specific shortcut words

### Feature Engineering
- Word count
- Average word length

### Text Vectorization
- Bag of Words (BoW)
- TF-IDF (Unigrams and Bigrams)
- Word2Vec

---

##  Models Implemented

- Logistic Regression
- Linear Support Vector Machine (Linear SVM)
- K-Nearest Neighbors (KNN)
- Multi-Layer Perceptron (MLP Neural Network)

---

##  Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Macro F1
- Confusion Matrix
- Learning Curves

---

##  Dataset

The dataset contains **2,015 Turkish news articles**.

After preprocessing:
- Removed missing values and duplicates
- Removed very short articles
- Final dataset size: **1,833 articles**

---

##  Best Results

| Model | Feature Representation | Accuracy |
|------|------|------|
| Linear SVM | TF-IDF | 98% |
| Logistic Regression | TF-IDF | 96% |
| KNN | TF-IDF | 98% |
| MLP | TF-IDF | 98% |
| Word2Vec + Logistic Regression | Word2Vec | 95% |

The best-performing models were Linear SVM, KNN, and MLP with approximately **98% accuracy**.

---

##  Visualizations

The project includes:
- Confusion Matrix
- Learning Curves
- Model Comparison Table

