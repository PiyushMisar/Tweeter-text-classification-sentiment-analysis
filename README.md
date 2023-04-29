# Tweeter_Text_Classification

We performed sentiment analysis on dataset consists of 1600000 tweets taken from Kaggle. We performed data
cleaning using regex. We then tokenize the tweets and performed stemming process using Snowballstemmer. we
made Embedding matrix which is used in embedding layer in model to embedded a token into it's vector
representation, that contains information regarding that token or word.We have used GloVe for vectorized
representation of words.Model training is done using LSTM which is an artificial neural network algorithm used in
Deep learning. We used ADAM optimizer and Accuracy metric to monitor performance of our model.We saved our
model in .h5 file format to store weights and model configuration.Streamlit library is used make interactive web app
of our model.We used AWS platform to deploy.
