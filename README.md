Sentiment Analysis of Financial News for Stock Market Prediction
This project leverages Natural Language Processing (NLP) and Deep Learning to analyze the sentiment of financial news articles and predict the likely market trend associated with them. The ultimate goal is to assist in understanding how news headlines might influence investor sentiment and subsequently affect stock prices.
Project Overview
We built a sentiment analysis pipeline that:
Preprocesses financial news headlines.
Converts text to numerical form using GloVe word embeddings.
Trains a neural network using CNN + Bidirectional LSTM to classify the sentiment as positive or negative.
Visualizes performance using confusion matrix, accuracy score, ROC curve, and more.
This can be a useful tool for financial analysts, traders, and researchers who want to quantify the emotional tone in market-related news.
| Technology               | Description                                                        |
| ------------------------ | ------------------------------------------------------------------ |
| **Python**               | Core programming language for scripting and modeling               |
| **TensorFlow & Keras**   | Deep learning framework used to build and train the neural network |
| **NLTK**                 | For text preprocessing (stopword removal, tokenization, etc.)      |
| **GloVe Embeddings**     | Pretrained word vectors used to convert text into dense vectors    |
| **Scikit-learn**         | For performance evaluation (accuracy, confusion matrix, ROC AUC)   |
| **Matplotlib & Seaborn** | Data visualization libraries                                       |
| **Google Colab**         | Development environment used for training and experimentation      |


Sample Results
Test Accuracy: 78%
AUC Score: 0.78
Model: CNN + Bidirectional LSTM
Input Representation: GloVe word embeddings (300d)
