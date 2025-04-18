# NLP-SentimentAnalysis
Natural Language Processing (NLP): This project analyze sentiment by classifying in scraped Vietnamese reviews on App Store and Google Play 
- Preprocess the review data
- Apply the Word2Vec/PhoBERT vectorization
- Train the Machine Learning model with processed data
- Model evaluation
- Apply the model on new data

Problem statement:
- App creators want to understand user behavior but fear of handling data
- The amount of data to process is huge (Big data)
- Lack of good sentiment analysis tools 

Solution:
- Natural Language Processing

Model used:
- Word2Vec (word to vector)
- PhoBERT (open-source model which optimize for vietnamese)

Techniques:
- Stopwords; normalization; tokenization; Parts-of-Speech (POS)
- Standard scaler; PCA

Limitation & Future development:
- Apply hyperparameter tuning 
- Add domain knowledge features 
