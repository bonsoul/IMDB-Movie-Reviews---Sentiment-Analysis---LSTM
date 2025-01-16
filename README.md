# IMDB Movie Reviews Sentiment Analysis Using LSTM

This project demonstrates a deep learning approach to performing sentiment analysis on the **IMDB Movie Reviews Dataset**. Using an LSTM-based neural network, the notebook classifies reviews as **positive** or **negative**, showcasing the power of recurrent layers for text analysis tasks.

## Key Features
- **Dataset**: IMDB movie reviews dataset with labeled sentiment (positive/negative).
- **Preprocessing**: 
  - Text tokenization and padding.
  - Conversion of words to indices using an embedding layer.
  - Removal of unnecessary characters for cleaner data input.
- **Model Architecture**: 
  - An LSTM-based sequential model with the following layers:
    - **Embedding**: To transform word indices into dense vector representations.
    - **LSTM**: To capture temporal dependencies and context in text data.
    - **Dense**: For binary classification with a sigmoid activation.
- **Model Training**:
  - Binary crossentropy as the loss function.
  - Adam optimizer for efficient gradient descent.
  - Dropout and recurrent dropout for regularization.
- **Evaluation**: Accuracy and loss metrics on the validation dataset.
- **Visualization**:
  - Training and validation performance graphs.
  - Confusion matrix for model predictions.

## Results
- The model achieves reasonable accuracy, demonstrating its ability to generalize on unseen data.
- Performance highlights the effectiveness of LSTM for sequential text data.

## Dependencies
- Python
- TensorFlow/Keras
- NumPy
- Matplotlib
- Pandas

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/IMDB_Movie_Reviews_Sentiment_Analysis_LSTM.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebook:
   ```bash
   jupyter notebook IMDB_Movie_Reviews_Sentiment_Analysis_LSTM.ipynb
   ```

## Key Takeaways
This project showcases how to preprocess text data, use embeddings, and apply LSTM models for sentiment analysis. It is a great starting point for learning about deep learning in natural language processing (NLP).
