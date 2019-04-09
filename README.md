# Sentiment-Analysis
I Designed and developed rating prediction algorithm based on 
Python and Machine Learning for restaurants using Yelp review dataset.
My task was to predict if a review is either bad or good, so I just grab reviews that are
either 1 or 5 stars from the yelp dataframe. We can store the resulting reviews in a new
dataframe called yelp_class. In that I used pandas, numpy, matplotlib, seaborn, Natural
language toolkit, sklearn. Leveraged Supervised machine learning algorithms like naïve bayes 
classifier and Bow model. So I also checked the correlation between stars and the length. Dataset 
consisted over 10000 Yelp reviews (positive and negative) and the algorithm achieved average 
accuracy of 92%. The multinomial Naive Bayes classifier is suitable for classification with 
discrete features (e.g., word counts for text classification). The multinomial distribution
normally requires integer feature 
counts. However, in practice, fractional counts such as tf-idf may also work.
