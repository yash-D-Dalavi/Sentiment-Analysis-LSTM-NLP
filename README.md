# 🎬 Movie Review Sentiment Analysis using Bidirectional LSTM

### 📌 Project Overview
This project implements a Deep Learning model to classify movie reviews as Positive or Negative using the IMDB dataset. By leveraging **Bidirectional Long Short-Term Memory (LSTM)** networks, the model captures contextual information from both ends of a sentence.

### 🛠️ Tech Stack
* **Framework:** TensorFlow / Keras
* **Language:** Python
* **Model Architecture:** Embedding -> Bidirectional LSTM -> Global Max Pooling -> Dense
* **Dataset:** Keras IMDB Dataset (50,000 reviews)

### 📊 Results
* **Accuracy:** ~86%
* **Loss:** Optimized using Binary Crossentropy
* **Optimizer:** Adam

### 🚀 How to use
1. Clone the repo.
2. Open the `.ipynb` file in Google Colab.
3. Run all cells to train or use the `predict_sentiment()` function for custom reviews.
