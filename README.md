# Next-Word-Predictor

This project implements a **Next Word Prediction** model using **Long Short-Term Memory (LSTM)** neural networks, designed to suggest the next word in a given text sequence. By leveraging NLP techniques, this model can enhance typing suggestions and assist in generating text.

## Project Overview

- **Goal**: To predict the next word in a text sequence based on previous words.
- **Libraries Used**: `random`, `pickle`, `heapq`, `numpy`, `pandas`, `matplotlib`, `nltk`, `tensorflow.keras`.
- **Model Architecture**: LSTM-based sequential model with dense and activation layers to process sequential text data.

## Key Steps

1. **Data Preprocessing**: Tokenizes input text and prepares sequences using `nltk` tokenizer.
2. **Model Architecture**: LSTM model created using `tensorflow.keras` with dense and softmax layers.
3. **Prediction**: The model predicts the next word(s) by analyzing input sequences and selecting the most likely continuation.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/riz330/Next-Word-Predictor.git
   cd Next-Word-Predictor
