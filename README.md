# nlp-sentiment-analysis-using-bigrams-and-naive-bayes
This project implements sentiment analysis using bigrams and the Naïve Bayes classifier from TextBlob. A dataset of 10,000 positive and negative sentences is used for training.


## How the Model is Trained:

A dataset of 10,000 positive and negative sentences is used for training.


Stopwords are removed using NLTK's stopword list.


Sentences are tokenized and converted into bigrams (2-word sequences).
                                                    

Each sentence is labeled as positive (pos) or negative (neg) using TextBlob's sentiment polarity.


The Naïve Bayes classifier from TextBlob is trained using these bigram-based labeled sentences.
    

The classifier is then used to predict sentiment for new text inputs.


