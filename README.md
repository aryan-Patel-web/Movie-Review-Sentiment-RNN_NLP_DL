# Movie Review Sentiment Analysis with Simple RNN

This repository provides an end-to-end deep learning solution for sentiment analysis of movie reviews using a Simple RNN architecture. The project demonstrates how to preprocess text data, train a neural network, and deploy the model as an interactive web application.

## Features

- **Data Preprocessing:** Tokenization, word indexing, and sequence padding for uniform input.
- **Deep Learning Model:** SimpleRNN with embedding layer for semantic understanding.
- **Training & Evaluation:** Early stopping and performance evaluation on the IMDB dataset.
- **Web Deployment:** Streamlit app for real-time sentiment prediction on user-input reviews.
- **Robust Preprocessing:** Handles punctuation and unknown words for real-world usability.

## Getting Started

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/movie-review-sentiment-rnn.git
   cd movie-review-sentiment-rnn
   ```

2. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

3. **Train the model (optional):**
   Use the provided Jupyter notebooks to train and save your own model.

4. **Run the Streamlit app:**
   ```
   streamlit run main.py
   ```

## Usage

- Enter a movie review in the web app.
- The app will display the encoded input, raw prediction score, and the predicted sentiment (positive or negative).

## Project Structure

- `embedding.ipynb` – Word embedding and preprocessing exploration.
- `simpleRNN.ipynb` – Model training and evaluation.
- `main.py` – Streamlit web app for deployment.
- `requirements.txt` – List of required Python packages.


**Contributors:**  
- Name - Aryan patel

---

**Acknowledgements:**  
- [IMDB Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
- TensorFlow, Keras, Streamlit
