# spam-classifier
It consists of a classification between ham and spam emails. The dataset has been obtained from the open-source Apache SpamAssassin Project (http://spamassassin.apache.org/old/publiccorpus/).

The methods used for text processing are: punctuation removal, lowercase conversion, stemming, urls and numbers replacement, and removal of words without information.

For the classification, 4006 emails were used for training and 1972 emails for testing, with a total vocabulary (provided by training) of 33k words. The model used for the classification was the Logistic Regression model and it obtained a 97.25% accuracy in the training set. For testing, a precission of 97.14% and a recall of 95.85% were obtained.
