This project implements a Sentiment Analysis system using Deep Learning techniques to classify movie reviews from IMDb as either positive or negative. The sentiment classification is achieved through the use of a Long Short-Term Memory (LSTM) network, a type of Recurrent Neural Network (RNN) that is particularly effective in processing sequences of text, such as sentences in reviews.

The model was trained using a large dataset of IMDb reviews, where each review is labeled as either positive or negative. The sentiment prediction is based on the textual content of the review, making it a great example of Natural Language Processing (NLP) in action.

The project includes an interactive user interface built using Gradio, which allows users to input movie reviews and receive real-time predictions on whether the review has a positive or negative sentiment. This provides a practical, user-friendly way to showcase the effectiveness of the sentiment analysis model.

Key Features:
LSTM Model: The model uses an LSTM architecture, well-suited for text sequence data, to classify the sentiment of movie reviews.
Tokenization and Padding: Text data is preprocessed using tokenization and padding techniques to ensure uniform input length for the model.
Real-time Prediction: Gradio is used to create a simple interface where users can input a review and get a sentiment prediction instantly.
