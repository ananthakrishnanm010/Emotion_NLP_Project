#  NLP Emotion Classification using Machine Learning and Deep Learning

##  Project Overview

This project focuses on **Emotion Classification** using Natural Language Processing (NLP). The objective is to classify text into one of six emotion categories by applying text preprocessing techniques, TF-IDF feature extraction, and multiple machine learning/deep learning models.

The project compares the performance of:
- Logistic Regression
- Support Vector Machine (SVM)
- Artificial Neural Network (ANN)

---

##  Dataset

**Dataset:** DAIR-AI Emotion Dataset

Source:
https://huggingface.co/datasets/dair-ai/emotion

The dataset consists of text samples labeled with one of six emotions:

-  Joy
-  Sadness
-  Anger
-  Love
-  Fear
-  Surprise

---

##  Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Gensim

---

##  Project Workflow

### 1. Data Loading
- Load the Emotion dataset from Hugging Face
- Explore dataset structure

### 2. Exploratory Data Analysis (EDA)
- Check dataset information
- Analyze class distribution
- Inspect missing values
- Explore text samples

### 3. Text Preprocessing

The following preprocessing steps are applied:

- Duplicate removal
- Punctuation removal
- Lowercasing
- Tokenization
- Stopword removal
- Lemmatization

---

##  Feature Extraction

TF-IDF is used to convert text into numerical feature vectors suitable for machine learning models.

---

##  Train-Test Split

The dataset is divided into training and testing sets before model training.

---

##  Models Implemented

### 1. Logistic Regression
- Baseline machine learning classifier
- Optimized using increased iterations

### 2. Support Vector Machine (Linear SVM)
- LinearSVC classifier
- Hyperparameter tuning using GridSearchCV

### 3. Artificial Neural Network (ANN)

Architecture:

- Input Layer
- Dense (512, ReLU)
- Batch Normalization
- Dropout (0.3)
- Dense (256, ReLU)
- Batch Normalization
- Dropout (0.3)
- Dense (128, ReLU)
- Dropout (0.2)
- Output Layer (Softmax, 6 classes)

---

##  Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

##  Project Structure

```
NLP_Parallel_Project.ipynb
README.md
```

---

##  Future Improvements

- Word2Vec embeddings
- GloVe embeddings
- Attention mechanisms
- Hyperparameter optimization
---

##  Libraries Used

- pandas
- numpy
- nltk
- gensim
- scikit-learn
- tensorflow
- matplotlib



##  Acknowledgements

- Hugging Face Datasets
- DAIR-AI Emotion Dataset
- Scikit-learn
- TensorFlow
- NLTK

##  Contributions

| Contributor | Responsibilities |
|--------------|------------------|
| **Ananthakrishnan** | • Created the project skeleton and notebook structure.<br>• Imported and configured all required libraries.<br>• Implemented the complete NLP preprocessing pipeline.<br>• Developed and evaluated the **Logistic Regression** and **SVM** models.|
| **Priya** | • Implemented **TF-IDF** feature extraction for text vectorization.<br>• Designed, trained, and evaluated the **Artificial Neural Network** model for emotion classification. |                       |

