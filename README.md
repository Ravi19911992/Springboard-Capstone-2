# Classification of gender using Tweets(text) data
# Objective
Sentiment analysis is famous among major brands. It is the way to identify the tone and emotions expressed through written or spoken online communication. It is famous with big companies like
* Twitter
* Amazon
* Facebook
* Netflix

The goal of this project is to simply view a Twitter profile text data and judge whether the user was a male, a female, or a brand (non-individual). NLP is used and its different methods pave the way for achieving a solution for performing the analysis. This is useful for the prospective client in determining a particular gender in analyzing well, based on seeing a user’s tweet or a profile.

# Target audience
This is mainly useful for a prospective client in determining a particular gender in analyzing well, based on seeing a user’s tweet or a profile. This helps determine on how the gender distinction and the tweets being made work better.

# Dataset
This data set was used to train a CrowdFlower AI gender predictor. This dataset was from a Kaggle competition. The dataset contains 20,000 rows, each with a username, a random tweet, account profile and image, location, and even link and sidebar color. 

# Approach
* Pulling the data from csv files
* Analyzing and cleaning the data from the text and description columns, and also combining them both and performing analysis by techniques like Lemmatization, Stopwords etc.
* Creating a BOW(Bag of words) model for Machine learning to be able to understand.
* Using fastai deep learning library to perform transfer learning and using pretrained models to classify the gender.
* Also, creating different ML models from scratch to measure how well they perform using metrics like accuracy, confusion matrix and provide insights and recommendations from it.
* Identify challenges with approach / results and provide recommendations on how to improve for future analysis.

# Deliverables
Associated code, paper, and presentation are included in the associated files.
