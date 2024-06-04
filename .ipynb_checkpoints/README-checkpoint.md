# kaggle_disaster_tweets
Natural Language Processing with Disaster Tweets (Kaggle Competition for Getting Started)

Based on my recently developing interest in decision science and NLP, I decided to choose this project to revise some previously learned ML skills and start building a GitHub portfolio.

## Clean and Prep the data

The first step was to load and study the data. We have a training set of 7613 tweets, out of which all 7552 (~99%) have a keyword tag but nearly 33% are missing location tags. Additionally, in this dataset, every tweet has been classified as a disaster tweet (target = 1) or not (target = 0).

### Data Cleaning

In order to be able to better analyze the tweets, we removed the following from the tweet texts:
1. Puncutation
2. Special Characters
3. URL links
4. Numbers
5. Emojis

After cleaning the tweet texts, we lemmatize the words in the tweets using the *pattern* library. 

## Preliminary Analysis

At this stage

![image info](./images/lemmatized_word_cloud.png)
