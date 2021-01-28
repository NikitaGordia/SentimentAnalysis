# Sentiment analysis

Problem: Given an IMDB dataset with reviews, we need to estimate sentiment

### Project:
```
root
└─── data
│   │   └───dev
│   │   |   feed_count.npz
│   │   |   feed_tfidf_lite.npz
│   │   submission.csv
│   │   test.csv
│   │   train.csv
└─── notebooks
    │   data.ipynb
    │   model.ipynb
    │   model_ensamble.ipynb
```

### Notebooks
1. data.ipynb - notebook for data cleaning and efficient
preprocessing.
2. model.ipynb - notebook with model selection.
2. model_ensemble.ipynb - notebook for estimation of performance
improvements via usage of ensemble techniques.
   
### Data
1. feed_count.npz - preprocessed docs and vectorized with CountVectorizer
2. feed_tfidf_lite.npz - preprocessed docs and vectorized with TfIdf.