MVP: Classification

AIM & DATASET
I am working on a Kaggle dataset of Uber reviews from 2013-2019 with star ratings from 1-5. Each review document is approximately 100 words long and there are 2347 reviews in the document. The aim is to find the topics commonly associated with positive and those with negative reviews, so it is easy for Uber to address the issues without needing to read through each review. 

PROCESS
I removed the documents rated 3 as they were neutral and kept only 4 and 5 as positive review and 1 and 2 as negative review. 
https://github.com/bipsita/NLP/blob/main/StarDistribution.png

TOOLS
Spacy for cleaning, (TF_IDF vectorizing), and NMF for topic modeling

TOPIC MODELS
Here are the top 4 topic models. 
https://github.com/bipsita/NLP/blob/main/topic_models.png

Finally I did some sentiment analysis
https://github.com/bipsita/NLP/blob/main/Sentiment_analysis0.png
https://github.com/bipsita/NLP/blob/main/Sentiment_analysis0.png

NEXT STEPS
Next I would like to fine tune my topic model, possibly use Corax. I would like to use LDA, to get myself familiar with it, but am not sure if my document size is good for LDA. Finally, I would like to build a logistic regression model to forecast good or bad review based on topics. 
