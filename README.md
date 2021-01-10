# Bi-LSTM_with_attention

## Task:
Train a Bi-LSTM with Attention on IMDB movie review data and use the trained model to classify live news crawled from livemint.com

## Training 
1. Used IMDB movie review data - 80% train, 10% validation, 10% test
2. Used Glove (6B) embeddings for words, embedding dimension - 300
3. Max Sequence Length - 200

## Test Results
Test Set Accuracy - 80.41%

## Livemint crawling
Crawling is done using beautiful soup html parser and requests (python tool for get requests)

## Sentiment on articles
1. Break the article into sentences.
2. Get polarity for each sentence.
3. if max sentences are positive - return positive as overall sentiment, negative otherwise.

Code is self explanatory, please raise issues in case if I've missed anything or if you want me to add something.
I've used many resources in making this, hence won't claim ownership.
