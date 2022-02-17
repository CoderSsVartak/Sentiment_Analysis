# Sentiment_Analysis
Sentiment Analysis task using Recurrent Neural Network

Used a recurrent neural network to capture the sentiments in a sentence/tweet.
The model is trained on 20 words per sentence as the average length of tweets is about 15 after removing the stopwords.

## Libraries used:

1. Tensorflow: as a backend for keras
2. Keras: API used for building the RNN model
3. NLTK: Text preprocessing
4. Pandas: Dataframe usage
5. Numpy: Text Preprocessing and Vectorization
6. re: Text preprocessing
7. pickle: to load the dataset pickle file
8. gensim: For glove model for representing words in vector form

**The code also uses pre-trained Embedded layer which reduces the number of trainable parameters.**

## **Version 1:**
  
* The model uses **3 Uni-directional Recurrent layers** and **2 Dense Layers** with **'relu' activation** function for hidden layers and **'sigmoid' for the output layer** 
  
* The model outputs approximately 70% precision on the test dataset
