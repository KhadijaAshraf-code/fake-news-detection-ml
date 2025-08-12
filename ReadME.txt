# 📰 Fake vs Real News Detection

## 📌 Overview
This project uses Natural Language Processing (NLP) and Machine Learning to classify news articles as **fake** or **real**.

## 📊 Dataset
- Source: [Kaggle Fake News Dataset](https://www.kaggle.com)
- Size: ~20,000 articles
- Features: Title, text, label (fake/real)

## ⚙️ Steps Performed
1. Data Cleaning (removing punctuation, stopwords, and special characters)
2. Tokenization & Vectorization (TF-IDF)
3. Model Training (Logistic Regression)
4. Model Evaluation (Accuracy, Precision, Recall, F1-score)
5. Visualization (Confusion Matrix, word clouds)

## 📈 Results
- Accuracy: **XX%**
- Best Model: Logistic Regression

## 🚀 How to Run
```bash
pip install -r requirements.txt
python src/model_training.py

##📂 Dataset
This project uses https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset   from above link from Kaggle.
Due to size and licensing restrictions, the dataset is not included in this repository.

To download the dataset:

Create or log in to your Kaggle account.
Go to the dataset page: Dataset Link
Click on Download to get the dataset files.
Place the downloaded files in the data/ folder of this project.


