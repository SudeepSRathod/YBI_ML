**Women Cloth Reviews Prediction with Multi Nomial Naive Bayes**
Naive Bayes is a probabilistic algorithm family based on Bayes’ Theorem. It’s “naive” because it presupposes feature independence, which means that the presence of one feature does not affect the presence of another (which may not be true in practice).
Multinomial Naive Bayes is a probabilistic classifier to calculate the probability distribution of text data, which makes it well-suited for data with features that represent discrete frequencies or counts of events in various natural language processing (NLP) tasks.
Multinomial Distribution The term “multinomial” refers to the type of data distribution assumed by the model. The features in text classification are typically word counts or term frequencies. The multinomial distribution is used to estimate the likelihood of seeing a specific set of word counts in a document.
The probability mass function (PMF) of the Multinomial distribution is used to model the likelihood of observing a specific set of word counts in a document. It is given by:
P(D|c) = \frac{T_{c}!}{\prod_{i=1}^{V}(x_{i}!)}\prod_{i=1}^{V}\left ( \frac{\theta_{c,i }^{x_i}}{x_i !} \right )

**Objective**
The objective of this project is to build a machine learning model that can predict the sentiment of women's clothing reviews. Specifically, we aim to:

Classify Reviews: Develop a model to classify reviews into different rating categories (e.g., 1-5 stars or positive/negative).
Text Analysis: Utilize natural language processing (NLP) techniques to extract meaningful features from the text reviews.
Model Evaluation: Assess the performance of the chosen model using appropriate metrics such as accuracy, precision, recall, and F1-score.
Improve Customer Experience: By understanding customer sentiment, provide insights to businesses to improve their products and services.
