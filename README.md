# Sentiment Analysis on IMDB Movie Reviews using LSTM

This project implements a Sentiment Analysis system using a Long Short-Term Memory (LSTM) model to classify IMDB movie reviews as positive or negative. The dataset consists of labeled movie reviews and the model is built using TensorFlow and Keras.

## Features

- Data preprocessing using tokenization and padding.
- Sentiment classification using an LSTM neural network.
- Model evaluation using accuracy and loss.
- Predictive system for custom reviews.
- Model and tokenizer saved for future use.

## Project Structure

- [IMDB_Dataset.csv](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews): Dataset containing labeled reviews.
- model.h5: Saved LSTM model.
- tokenizer.pkl: Tokenizer used for text preprocessing.
- main.py: The implementation file containing all the model training, evaluation, and prediction logic.

## Dataset
- Download the [IMDB_Dataset.csv](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) from [Kaggle](https://www.kaggle.com/) and place it in the project directory.

## Model Details
- Tokenizer: Limited to the top 5000 words.
- Sequence Length: 200 tokens.
- Embedding Layer: 128-dimensional embeddings.
- LSTM Layer: 128 units with dropout and recurrent dropout.
- Activation: Sigmoid for binary classification.

## Evaluation Metrics
- Loss: Binary Cross-Entropy
- Accuracy: Percentage of correctly classified reviews

## Future Improvements
- Implement Bidirectional LSTMs for improved accuracy.
- Add sentiment confidence scores.
- Expand the model to support additional datasets.

## Contributing
- Contributions are welcome! Feel free to submit a pull request or open an issue.

### Happy Coding! 🚀
