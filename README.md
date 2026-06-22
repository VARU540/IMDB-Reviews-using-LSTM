# 🎬 IMDB Movie Review Sentiment Analysis using LSTM

## 📌 Overview

This project performs Sentiment Analysis on IMDB movie reviews using a Long Short-Term Memory (LSTM) neural network. The model classifies movie reviews as **Positive** or **Negative** based on the textual content of the review.

The project demonstrates the application of Natural Language Processing (NLP) and Deep Learning techniques for binary text classification.

---

## 🚀 Features

* Text preprocessing and cleaning
* Tokenization and sequence padding
* Word Embedding layer
* LSTM-based Deep Learning model
* Binary sentiment classification
* Model evaluation using accuracy metrics
* Visualization of training and validation performance

---

## 📂 Dataset

The project uses the IMDB Movie Review Dataset containing **50,000 reviews** equally distributed between positive and negative sentiments. The dataset includes:

| Column    | Description               |
| --------- | ------------------------- |
| review    | Movie review text         |
| sentiment | Positive / Negative label |

---

## 🛠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 🧠 Model Architecture

Input Review Text
↓
Text Preprocessing
↓
Tokenization & Padding
↓
Embedding Layer
↓
LSTM Layer
↓
Dense Layer (Sigmoid)
↓
Sentiment Prediction

### Model Components

1. Embedding Layer
2. LSTM Layer
3. Dense Output Layer
4. Sigmoid Activation Function

**Loss Function:** Binary Crossentropy

**Optimizer:** Adam

---

## 📊 Workflow

### 1. Data Loading

* Load IMDB review dataset
* Explore dataset structure

### 2. Data Preprocessing

* Remove unwanted characters
* Convert text into sequences
* Pad sequences to fixed length

### 3. Model Building

* Create Embedding Layer
* Add LSTM Layer
* Add Dense Output Layer

### 4. Model Training

* Train using training dataset
* Validate using validation dataset

### 5. Evaluation

* Calculate Test Accuracy
* Analyze predictions

---

## 📈 Results

The LSTM model successfully learns sentiment patterns from movie reviews and achieves high classification performance on unseen reviews.

Evaluation Metrics:

* Accuracy
* Loss
* Training Curves

---

## 📷 Sample Prediction

Review:
"This movie was absolutely fantastic and enjoyable."

Prediction:
Positive Sentiment ✅

Review:
"The plot was boring and a complete waste of time."

Prediction:
Negative Sentiment ❌

---

## 📁 Project Structure

IMDB-Reviews-using-LSTM/

├── sentiment_analysis.py.ipynb

├── IMDB Dataset.csv

├── README.md

---

## 🎯 Future Improvements

* Bidirectional LSTM
* GRU-based Model
* BERT Transformer Model
* Attention Mechanism
* Streamlit Web Application Deployment
* Real-Time Review Analysis API

---

## 📚 References

* TensorFlow Documentation
* Keras Documentation
* IMDB Movie Review Dataset 
* NLP and Deep Learning Research Papers

---

## 👨‍💻 Author

Varun Chaudhari

Final Year Computer Engineering Student

Interested in Data Science, Machine Learning, Deep Learning and NLP.
