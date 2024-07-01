This project is a Fake News Detector that utilizes the Gensim word embedding technique trained on Google News. The model processes text data to detect the authenticity of news articles. Here is an overview of the techniques and models used:

Gensim Word2Vec: The word embeddings are created using Gensim's implementation of the Word2Vec model, which has been trained on the Google News dataset. This model provides high-quality word embeddings where similar and related words have almost similar vector representations.

K-Nearest Neighbors (KNN): Among various classifiers tested, the KNN classifier produced the best results. KNN works particularly well with the 300-dimensional Glove vectors because of their high-quality embeddings. The similar and related words being closely placed in the vector space enhances the classifier's performance.

The model is trained on this data:('https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets')
