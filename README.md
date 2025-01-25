# Decoding-Review-Impact-A-Study-on-Sentiment-Length-and-Readability-in-Movie-Reviews

Research Question - What factors influence the likelihood of receiving a higher overall voting/perceived helpfulness in movie and TV show reviews?

Hypothesis -

1. The readability of a review has a curvilinear relationship with perceived helpfuless, i.e. reviews with less readability score have less vote count. But as this score increases, the vote count increases as well. However, after a certain threshold value, the increase in readability score results in a decrease in vote count.

2. The length of a review has a curvilinear relationship with perceived helpfuless, i.e. shorter length reviews have less vote count, but as the review length increases, the vote count increases as well. However, after a certain threshold value, the increase in review length results in a decrease in vote count.

3. The two extreme sentiments of a review, i.e. strongly positive and strongly negative, correspond to higher vote count, compared to neutral sentiment reviews.


This is an in-depth study of the above research question involving Data Summarization and Descriptive Analysis, creating corpus, tokenization and pre-processing, wordclouds, sentiment analysis, Topic Modelling via Latent Dirichlet Allocation (LDA), and finally feature engineeing and the testing of the three hypothesis. A Negative Binomial Regression model is also fitted to check the statistical significance of the variables in the three hypothesis, i.e. review_length, polarity, and readability, followed by its interpretation.
