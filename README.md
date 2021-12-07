# Was your ride Uber-smooth?
November 1-12, 2021

Uber receives many reviews: positive and negative. In this Kaggle global dataset of 2247 Uber reviews, spanning from 2013 to 2019, we analyze text to arrive at meaningful topics related to the positive and the negative reviews. The reviews are 100 words long on average, with a majority rated at 1-star. The text data is cleaned of numbers, punctuations, and Unicode characters, and tf-idf vectorization is performed on it. NMF and LDA models are used for topic modelling. 

#### Tools

 - Pandas and Numpy are used for data manipulation; 
 - NLTK and Spacy are used for data cleaning; 
 - ScikitLearn and Gensim are used for training models; 
 - Seaborn and Matplotlib are used for visualization. 

Analysis shows a difference in average topic scores for 'on the road' experience and 'time'-related experience, but none for 'charge' or 'payment method' related experience. On working with negative reviews only, on a more recent subset of the data, the topic 'on the road' experience is replaced by 'customer service' experience. 

