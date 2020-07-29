# TCS-iON-Projects
Automate Detection of Different Sentiments from Paragraphs and Predict Overall Sentiment

Project 1 :-  
In this project I have used IMDB Dataset for predicting the sentiment of a particular movie review, whether that movie has a positive review or a negative review.
In this I’ve used three different types of deep neural networks, they are:
1. Densely connected Neural Network (Basic Neural network).
2. Convolutional Neural Network (CNN)
3. Long Short Term Memory (LSTM)


Importantly in this project I’ve also used Keras Embedding Layer and GloVe word embeddings to convert text to numeric form.

1. When I used Simple Neural Network then I got test accuracy of 73.61%.

2. When I used CNN then I got test accuracy of 83.46%.

3. When I used LSTM then I got test accuracy of 84.75%.


Your can download IMDB dataset from here :- 
https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/download

And download GloVe dataset from here :-
https://www.kaggle.com/rtatman/glove-global-vectors-for-word-representation?select=glove.6B.100d.txt

Project 2 :-  
In this project I've used the Keras built-in IMDB dataset. The imdb.load_data() function allows you to load the dataset in a format that is ready for use in neural network and deep learning models.
We quickly develop a small LSTM for the IMDB problem and achieve good accuracy. 
But the Recurrent Neural networks like LSTM generally have the problem of overfitting.


Dropout is a powerful technique for combating overfitting in your LSTM models
So, here we applies Dropout that can be applied between layers using the Dropout Keras layer. We can do this easily by adding new Dropout layers between the Embedding and LSTM layers and the LSTM and Dense output layers.

When I used LSTM with dropout then I got test accuracy of 88.05%.

