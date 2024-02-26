# Predicting Political Affiliations of Social Media Users

## Team Members

- **Haoyu Fu**  
  Email: [h6fu@ucsd.edu](mailto:h6fu@ucsd.edu)
- **Yixuan Zhang**  
  Email: [yiz119@ucsd.edu](mailto:yiz119@ucsd.edu)

Email: h6fu@ucsd.edu      yiz119@ucsd.edu

## Mentor

- **Haojian Jin**

# Background

**Traditional Polling**: relies on approaches such as surveying, phone calling, interviewing,
which are time consuming and requires a lot of human resources.

**Innovative Approach**: This project aims to explore novel ways to find people’s political
affiliations by utilizing machine learning and large language models, which can potentially
reduce the cost of polling.

# Data
**Data Source**: Twitter dataset from Kaggle containing tweets with hashtags #Biden and #Trump.

**Data Format**: After data cleaning, the data feature contains user IDs, tweet posting
times, and tweet text content.

**Pre-Processing**: Unnecessary information such as URL links, @ mentions, and tags were
removed from the tweets.

# Methods

### Text Processing**: 

The text content is the tweet component that we are most interested in. 
We made two different processing on the text data.

**Fine tuning and semantic embedding**: We fine tuned some large language models (LLMs)
with the tweet texts, and propted the LLMs to answer our questions on some political topics. 
Then we convert the responses into semantic embeddings for later processes.

**Sentiment clustering**: We also ran a sentiment analysis on the text to extract the
users’ emotions on the topics discussed. Then we clustered these processed data to
group similar users together.

# Results

# References