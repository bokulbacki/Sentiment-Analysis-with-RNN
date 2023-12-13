We'll be training the model on a dataset of movie reviews from IMDB that have been labeled either "positive" or "negative". Since this is text data, words in a sequence, we can use an RNN to build a model that doesn't only consider the individual words, but the order they appear in. This leads to a powerful model for making these types of sentiment predictions.
In this notebook, you'll implement a recurrent neural network that performs sentiment analysis.
