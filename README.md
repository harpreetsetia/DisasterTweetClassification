# DisasterTweetClassification
A tweet analysis model utilizing a Natural Language Processing framework' Bidirectional Encoder Representations from Transformers to identify tweets that represent actual disasters compared to the ones that don't.

## Machine Learning and Deep Learning
Inspired by a [Kaggle]([https://www.kaggle.com/c/nlp-getting-started/overview]) competition, I built an NLP classifier, which would utilize a state-of-the-art pre-training technique called Bidirectional Encoder Representations from Transformers (BERT), which I implement through the Hugging Face API, to identify which tweets are representative of actual disasters and which are not. 

I have also included a sentiment analysis of each tweet to see if there is a correlation between sentiment and disaster classification and if the addition of sentiment improves model performance. With this approach, the model accurately classified which tweets represent disasters with a 0.924 accuracy.
