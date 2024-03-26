# Disaster Management Classification
Disaster management using twitter data. The following scripts contain implementation of Bidirectional LSTM architecture to predict whether a tweet is corresponding to an actual disaster or not.  
Preprocessed the tweets and embedded them for the BiLSTM layers.
I used some regularisation techniques like Dropout, and ReduceRLonPlatue and added earlystopping to avoid overfitting.
The validation accuracy came out to be ~80%.
Also added a naive bayes approach to get a baseline score.
