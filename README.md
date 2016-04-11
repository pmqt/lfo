# lfo
Current Project(s): Naive Bayesian Classifier, Markov Chain Poetry Generator

Resources:
http://www.nltk.org/book/ch06.html
Section 5

https://en.wikipedia.org/wiki/Naive_Bayes_classifier

My current idea for the classifier is to take a list of features in the format of a tuple containing the feature list and the label (i.e. ({'first-letter-capitalized':True,...}, Label)) and generate probabilities based upon these features. 

Also generating a lookup table for the probabilities is more optimal since searching a dictionary for a value is constant time (hell yeah)
