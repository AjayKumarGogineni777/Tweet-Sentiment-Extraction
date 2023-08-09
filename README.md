This is the code I used for the Kaggle Challenge on Tweet-Sentiment-Extraction : https://www.kaggle.com/competitions/tweet-sentiment-extraction

This notebook is a TensorFlow template for solving Kaggle's Tweet Sentiment Extraction competition as a question and answer roBERTa formulation. In this notebook, we show how to tokenize the data, create question answer targets, and how to build a custom question answer head for roBERTa in TensorFlow. Note that HuggingFace transformers don't have a TFRobertaForQuestionAnswering so we must make our own from TFRobertaModel
