# 🎬 IMDB Movie Review Sentiment Analysis

This project performs **sentiment analysis** on IMDB movie reviews using deep learning. It classifies reviews as either **positive** or **negative** based on the textual content. The trained model is also integrated into a simple web interface for real-time sentiment prediction.

---

## 🚀 Project Structure

- `IMDB_Movie_Review_Sentiment_Analysis.ipynb`  
  → Trains a neural network (LSTM) on IMDB dataset, saves model to `.h5` format.

- `Model_Testing_&_Web_Application.ipynb`  
  → Loads the trained model and allows users to input their own reviews for live predictions.

---

## 🧠 Model Overview

- **Dataset**: IMDB movie review dataset (25,000 training & 25,000 testing samples).
- **Preprocessing**: Tokenization, padding, vocabulary size limitation.
- **Model Architecture**: Embedding → LSTM → Dense layers.
- **Metrics**: Accuracy, loss, confusion matrix.

---

![image](https://github.com/user-attachments/assets/1fa3ec63-c838-4d82-bd5c-37e75a4e5d6e)
