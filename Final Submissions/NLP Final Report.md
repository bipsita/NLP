# Was your ride Uber-smooth?

#### Abstract

Uber receives many reviews: positive and negative. In this Kaggle global dataset of 2247 Uber reviews, spanning from 2013 to 2019, we analyze text to arrive at meaningful topics of positive and of negative reviews. Analysis shows a difference in average topic scores for 'on the road' experience and 'time'-related experience, but none for 'charge' or 'payment method' related experience. On working with negative reviews only on a more recent subset of the data, the topic 'on the road' experience was replaced by 'customer service' experience. 

#### Design

The aim of the project is to find the main topics of the positive and the negative reviews of Uber data. 

#### Data

Kaggle dataset is used of global Uber reviews from 2013-2019. The data contains 2247 reviews with a mean of 100 words per review. A majority of these reviews were rated at 1-star. 

#### Algorithms

The text data was cleaned of numbers, punctuations, and Unicode characters, and tf-idf vectorization is performed on it. NMF and LDA models are used for topic modelling. 

#### Tools

Pandas and Numpy are used for data manipulation; NLTK and Spacy are used for data cleaning; ScikitLearn and Gensim are used for training models; Seaborn and Matplotlib are used for visualization. 

#### Communication

In addition to the slides presented, the project will be posted on my Github. 

