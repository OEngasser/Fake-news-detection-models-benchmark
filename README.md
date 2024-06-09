# Fake-news-detection-models-benchmark
In the age of widespread and free sharing of information on the internet and social media, the dissemination
of false information or fake news has become increasingly problematic, especially in the political domain.
This phenomenon constitutes a scourge on many fronts, as it influences opinions, incites fear or hatred, and
ultimately seeks to steer decision-making. In this study, we propose to use approaches based on Artificial
Intelligence - Natural Language Processing and Machine Learning - to develop a model capable of effectively
performing the task of fake news detection by classifying articles as true or false. We favored a
benchmarking methodology to compare different models based on their performance in the task: 7 so-called
"traditional" Machine Learning classifiers optimized using grid search and cross-validation (Naive Bayes,
Random Forest, SVM, Logistic Regression, Passive-Aggressive, AdaBoost, and Gradient Boosting), and 7 Deep
Learning models built on a logic of increasing complexity, optimized by tuning hyperparameters (Simple
embedding network, simple RNN, LSTM, bidirectional LSTM, bidirectional LSTM + CNN, Word2Vec -
bidirectional LSTM + CNN, and BERT). The results highlight the superior performance of the model combining
Word2Vec with a bidirectional LSTM and a CNN (> 86% accuracy on unseen data), demonstrating the
effectiveness of a strategy combining an architecture that captures the sequentiality of language and an
architecture capturing local information, fueled by embeddings qualified in semantic representation. We
discuss the results and possible future pursuits of this work, and propose an applicative tool stemming from
this theme, namely an application called FactGuard, based on human and artificial intervention to combat
misinformation.
Keywords : artificial intelligence, machine learning, fake news, classification, politics.
