Emotion Classification Model: Predicts emotions from text (sadness, joy, love, anger, fear, surprise, neutral).
Data Cleaning: Converts text to lowercase, removes punctuation, and extra spaces.
Tokenization & Padding: Texts are tokenized and padded for uniform input size.
Word Embeddings: Uses spaCy pre-trained word vectors.
Model Architecture: Combines CNN and BiLSTM layers.
Training & Evaluation: Trained with early stopping; evaluates precision, recall, and F1-score.
