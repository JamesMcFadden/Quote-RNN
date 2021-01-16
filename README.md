# Quote-RNN
Predicting number of likes on quotes on goodreads.com with a recurrent neural network

Can wisdom be broken down word for word? That's what this project attempts to achieve through a recurrent neural network (RNN). Data on quotes from goodreads.com is scraped directly from the website, consisting of quote text, quote author, and number of likes. It is all combined into one large dataframe, and then processed using NLP techniques. Once this is accomplished, a word embedding is created using word2vec. This allows for quantifying the text data for use in the RNN, which at this point in time only used the quote text and number of likes, excluding authors.
