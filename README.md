# RNN-Analysis
Understanding analysis of RNN models in Stocks and Tweets Datasets

The analysis revolves discussing different levels of NLP techniques through which text processing can be done.<br />
Two datasets have used for analyzing performance of different NLP techniques and produce desired results.<br />

### Dataset 1: Stock Prediction Analysis
The dataset in consideration is a combination of the world news and stock price shifts. There are 25 columns of top news headlines for each day in the data frame. Class label ‘1’ indicates increase in stock price, whereas Class label ‘0’ indicates decrease or same stock price.<br />

Task:<br />
● Prediction of stock increase/decrease using NLP Techniques BOW and TF-IDF.<br />
● Training both the models using Random Forest Classifier and compare the results.<br />

### Dataset 2: Tweet Sentiment Analysis
The concerned data set is extracted from Twitter where tweets have been expressed in positive, negative and neutral sentiments for the U.S Airlines on the month of February 2015. Classification will be done upon the attribute “Airline Sentiment”.<br />

Task 1:<br />
● Training the tweets using word2vec and compare the performance of Skip gram and CBOW<br />
● Plotting the output of both models using t-SNE<br />

Task 2:<br />
● Compare the performance of LSTM and Bi-LSTM<br />
● Plotting Training and Validation Accuracy, Training and Validation Loss for both models.<br />

Task 3:<br />
● Compare the results of activations functions when applied in LSTM<br />
● Show desired results for sigmoid, tanh, ReLu and Leaky ReLu<br />
