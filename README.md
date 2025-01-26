# Decoding Review Impact: A Study on Sentiment, Length, and Readability in Movie Reviews

This study analyzes how textual metrics such as Sentiment Polarity, Review Length, and Readability Score affect user engagement in Amazon Movie Reviews. 

Research Question - What factors influence the likelihood of receiving a higher overall voting/perceived helpfulness in movie and TV show reviews?

Hypothesis -

1. The readability of a review has a curvilinear relationship with perceived helpfulness, i.e. reviews with less readability score have less vote count. But as this score increases, the vote count increases as well. However, after a certain threshold value, the increase in readability score results in a decrease in vote count.

2. The length of a review has a curvilinear relationship with perceived helpfulness, i.e. shorter length reviews have less vote count, but as the review length increases, the vote count increases as well. However, after a certain threshold value, the increase in review length results in a decrease in vote count.

3. The two extreme sentiments of a review, i.e. strongly positive and strongly negative, correspond to higher vote count, compared to neutral sentiment reviews.


This is an in-depth study of the above research question involving Data Summarization and Descriptive Analysis, creating corpus, tokenization, and pre-processing, word clouds, sentiment analysis, Topic Modelling via Latent Dirichlet Allocation (LDA), and finally feature engineering and testing of the three hypotheses. A Negative Binomial Regression model is also fitted to check the statistical significance of the variables in the three hypotheses, i.e. review_length, polarity, and readability, followed by its interpretation.
