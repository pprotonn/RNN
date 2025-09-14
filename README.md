
***

# RNN: IMDB Movie Review Sentiment Analysis with Simple RNN

Welcome to the **RNN** repository! This project demonstrates an end-to-end deep learning pipeline for sentiment analysis on the IMDB movie review dataset, utilizing a **Simple RNN** (Recurrent Neural Network) implemented with TensorFlow and Keras.

## 🚀 Project Overview

- **Objective:** Build, train, and deploy a deep learning model that classifies movie reviews as positive or negative sentiments.
- **Tech Stack:** 
  - Python
  - TensorFlow (Keras)
  - Streamlit for model deployment/UI
  - Jupyter Notebooks for data exploration and modeling

## 📁 Repository Structure

```
.
└── simpleRNN/
    ├── embedding.ipynb         # Exploration of embedding layers and word representations
    ├── simplernn.ipynb         # End-to-end RNN model: explanation, building, training, and evaluation
    ├── prediction.ipynb        # Interactive notebook for model predictions and testing
    ├── main.py                 # Streamlit app for real-time movie review sentiment classification
    └── simple_rnn_imdb.keras   # Pretrained Simple RNN model weights (IMDB dataset)
```

## 🧠 Features

- **Word Embedding Exploration:** Dive into how words are represented mathematically before feeding into the RNN (`embedding.ipynb`).
- **Model Building and Training:** Step-by-step construction and training of a Simple RNN for binary sentiment classification (`simplernn.ipynb`).
- **Interactive Prediction:** Use `prediction.ipynb` to experiment with sample predictions and model performance.
- **Web App Deployment:** A ready-to-run Streamlit script (`main.py`) for classifying user-provided reviews in real time.
- **Pretrained Model:** Contains a trained `.keras` model file for instant deployment and testing.

## 📦 Installation & Usage

1. **Clone the repo:**
   ```bash
   git clone https://github.com/pprotonn/RNN.git
   cd RNN/simpleRNN
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *(Make sure to include TensorFlow, Streamlit, and Jupyter in `requirements.txt`.)*

3. **Run the Streamlit app:**
   ```bash
   streamlit run main.py
   ```

4. **Explore Notebooks:**
   - Open `embedding.ipynb`, `simplernn.ipynb`, or `prediction.ipynb` in Jupyter to follow and rerun the experiments.

## 📝 Example: Sentiment Classification

Launch the web app and enter a movie review, e.g.:
> “The movie was an absolute masterpiece, with stellar performances.”

The app will output:
- **Sentiment:** Positive
- **Score:** `[model probability]`

## 💡 What You’ll Learn

- Practical use of RNNs for sequence data (text)
- Hands-on experience with word embeddings
- Building and deploying deep learning models with TensorFlow & Keras
- Creating interactive data-science apps with Streamlit

## 🤝 Contributing

Contributions are welcome! Please open issues or submit pull requests for new features, improvements, or bug fixes.

## 📜 License

MIT License

***

*Show your appreciation by starring ⭐ the repo if you find it useful!*

[1](https://github.com/pprotonn/RNN)
